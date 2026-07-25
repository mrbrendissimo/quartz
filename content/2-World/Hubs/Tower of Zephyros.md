---
tags:
  - Category/Hub
container: Test
MyContainer: "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
MyCategory: Encampment
obsidianUIMode: preview
mapCalc1: NaN
---




> [!NOTE|div-m] Parent Region: `INPUT[suggester(optionQuery(#Category/Region)):MyContainer]`


---
# General

Select Settlement: `INPUT[suggester(optionQuery(#Category/Region)):MyContainer]`

Select Category: `INPUT[inlineSelect(option(City +1500), option(Town +200), option(Village +80), option(Hamlet <80), option(Encampment), option(Keep), option(Fortress), option(Stronghold)):MyCategory]`



# NPCs

`BUTTON[button_person]` List important NPCs here. 

```dataviewjs
// 1) Hub’s vault-relative path
const hubPath = dv.current().file.path;

// 2) Helper to extract the path from a "[[path|alias]]" entry
function extractPaths(mc) {
  if (!mc) return [];
  const arr = Array.isArray(mc) ? mc : [mc];
  return arr
    .map(link => {
      const m = String(link).match(/\[\[(.*?)\|/);
      return m ? m[1] : null;
    })
    .filter(Boolean);
}

// 3) Find all Places whose MyContainer points to this Hub
const placePages = dv.pages(`"2-World/Places"`)
  .where(p => extractPaths(p.MyContainer).includes(hubPath))
  .values;
// collect their **paths**
const placePaths = placePages.map(p => p.file.path);

// 4a) Indirect People: whose MyContainer links to any of those placePaths
const indirect = dv.pages(`"2-World/People"`)
  .where(p => {
    const paths = extractPaths(p.MyContainer);
    return paths.some(path => placePaths.includes(path));
  })
  .values;

// 4b) Direct People: whose MyContainer links **directly** to this Hub
const direct = dv.pages(`"2-World/People"`)
  .where(p => extractPaths(p.MyContainer).includes(hubPath))
  .values;

// 5) Merge & dedupe by file path
const allPeople = [...indirect, ...direct];
const unique = Array.from(
  new Map(allPeople.map(p => [p.file.path, p])).values()
);

// 6) Build rows (Name clickable, Race, Gender, Associated Group)
const rows = unique.map(p => {
  const linkEl = dv.el("a", p.file.name, {
    href: "#",
    cls: "dataview-link",
  });
  linkEl.addEventListener("click", e => {
    e.preventDefault();
    app.workspace.openLinkText(p.file.path, dv.current().file.path);
  });

  const race = p.char_race ?? "";
  const gender = p.char_gender ?? "";
  let groups = p.Connected_Groups ?? [];
  if (!Array.isArray(groups)) groups = [groups];
  const assoc = groups.join(", ");

  return [linkEl, race, gender, assoc];
});

// 7) Render the table
dv.table(
  ["Name", "Race", "Gender", "Associated Group"],
  rows
);
```

# GM Notes

> [!warning]+ Read aloud
> You see an enormous tower floating on a billowy cloud a thousand feet overhead. The tower must be hundreds of feet tall, and its spire looks strangely like a pointy wizard’s hat. As the tower drifts closer, stairs made of clouds begin to form underneath it and descend toward you.

Map 1.3 shows the tower. The stairs are made of firm cloud stuff and spiral downward, stopping just short of the ground. They are sized for humans and safe to climb. After climbing the stairs for 1,000 feet, the characters stand in front of the tower’s entrance, on a cloud that feels as firm and safe as solid ground. If the characters enter the first floor of the tower, a cloud giant wizard named [Zephyros](https://www.dndbeyond.com/monsters/296828-zephyros) descends from the second floor (using a [levitate](https://www.dndbeyond.com/spells/2165-levitate) spell) to greet them.

[Zephyros](https://www.dndbeyond.com/monsters/296828-zephyros) is an eccentric cloud giant with windswept white hair, a wispy white beard, and a billowy purple robe adorned with gold stars. He poses no threat to Nightstone or the characters.

Ever since the ordning shattered, Zephyros has been using [contact other plane](https://www.dndbeyond.com/spells/2045-contact-other-plane) spells to find a way to set things right. Failed castings of the spell have driven him insane on multiple occasions. He has recovered from the insanity, yet it has accentuated his eccentricity. His magical investigations led him to Nightstone. He had nothing to do with the cloud giant attack on the settlement and is horrified to learn of the damage his fellow giants caused.

Zephyros holds “small folk” in higher regard than most giants. If the characters introduce themselves to him, a wide smile settles on the cloud giant’s face as he realizes they are the ones mentioned by the mysterious planar entities with which he has spoken. Convinced that the characters can restore the ordning, Zephyros offers to transport them to one destination of their choice in the North. That is the extent of his involvement. The planar entities with whom Zephyros has spoken via the [contact other plane](https://www.dndbeyond.com/spells/2045-contact-other-plane) spell warned him against taking a more direct hand in events. The party’s destination should coincide with Morak’s quest. After safely delivering the characters to their destination, Zephyros and his tower depart for the Moonshae Isles.

If the characters ask Zephyros to take them somewhere other than Bryn Shander, Goldenfields, or Triboar, Zephyros (eccentric wizard that he is) gets a little befuddled and ends up taking them to one of these places by accident.

[Zephyros](https://www.dndbeyond.com/monsters/296828-zephyros) is a [cloud giant](https://www.dndbeyond.com/monsters/16827-cloud-giant), with the following changes:

- Zephyros is neutral good.
- He has an Intelligence score of 18 (+4) and the Spellcasting action option described below.
- He carries a giant-sized [staff of the magi](https://www.dndbeyond.com/magic-items/4767-staff-of-the-magi) instead of a morningstar. As an action, he can make two melee attacks with the staff. Each attack has a +15 bonus to hit and deals 20 (3d6 + 10) bludgeoning damage on a hit, or 23 (3d8 + 10) bludgeoning damage if used with two hands. This damage is considered magical.
- He has a challenge rating of 13 (10,000 XP).

> [!NOTE]+ **_Zehpryos Spellcasting._**
>  Zephyros casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 17, +11 to hit with spell attacks):
>  At will: [message](https://www.dndbeyond.com/spells/2188-message), [prestidigitation](https://www.dndbeyond.com/spells/2213-prestidigitation), [ray of frost](https://www.dndbeyond.com/spells/2226-ray-of-frost)
>  2/day each: [gust of wind](https://www.dndbeyond.com/spells/2134-gust-of-wind), [levitate](https://www.dndbeyond.com/spells/2165-levitate), [magic missile](https://www.dndbeyond.com/spells/2176-magic-missile)
>  1/day each: [cone of cold](https://www.dndbeyond.com/spells/2037-cone-of-cold), [contact other plane](https://www.dndbeyond.com/spells/2045-contact-other-plane) (cast as 1 action), [greater invisibility](https://www.dndbeyond.com/spells/2128-greater-invisibility), [mass suggestion](https://www.dndbeyond.com/spells/2184-mass-suggestion), [nondetection](https://www.dndbeyond.com/spells/2199-nondetection), [Otiluke’s resilient sphere](https://www.dndbeyond.com/spells/2349-otilukes-resilient-sphere), [protection from energy](https://www.dndbeyond.com/spells/2220-protection-from-energy), [tongues](https://www.dndbeyond.com/spells/2281-tongues)

Zephyros’s tower has no fitting accommodations for small folk, but the cloud giant wizard allows the party to camp on the first floor. He requests that the characters confine their activities to the first floor and stay away from the second floor and the aerie. Zephyros controls the tower’s movements using a [navigation orb](https://www.dndbeyond.com/magic-items/5518-navigation-orb) (see [appendix B](https://www.dndbeyond.com/sources/skt/magic-items#NavigationOrb)) on the second floor.

The Tower of Zephyros Travel Times table summarizes how long it takes the tower to travel from Nightstone to Bryn Shander, Goldenfields, or Triboar. Regardless of their ultimate destination, the characters have at least one encounter en route (see the “Unfriendly Skies” section for details).

### Tower of Zephyros Travel Times
|Destination|Travel Time|
|---|---|
|Bryn Shander|624 hours (26 days)|
|Goldenfields|72 hours (3 days)|
|Triboar|275 hours (11½ days)|

### First Floor

The tower rests atop a cloud that feels solid underfoot. An open archway leads to an empty vestibule, at the back of which hangs a thin, translucent blue curtain that flaps in the breeze. Beyond the curtain lies a 100-foot-high hexagonal chamber containing a giant-sized wooden table and stone chair. Dangling from the ceiling by iron chains are six crystal spheres with [continual flame](https://www.dndbeyond.com/spells/2048-continual-flame) spells cast on them. The illuminated spheres keep the room brightly lit.

The tower’s second floor can be seen through a 20-foot-wide hole in the soaring ceiling.

### [](https://www.dndbeyond.com/sources/dnd/skt/a-great-upheaval#SecondFloor)Second Floor

This level of the tower has an 80-foot-high ceiling and tall, slender windows set with panes of stained glass. Furnishings include a giant-sized bed and an enormous wooden chest sealed by an [arcane lock](https://www.dndbeyond.com/spells/2003-arcane-lock) spell. Stone shelves protrude from the walls at heights of 20, 40, and 60 feet, and these shelves bear the weight of Zephyros’s vast collection of journals (see “Treasure”).

Floating 10 feet above the floor is a [navigation orb](https://www.dndbeyond.com/magic-items/5518-navigation-orb) (see [appendix B](https://www.dndbeyond.com/sources/skt/magic-items#NavigationOrb)) that [Zephyros](https://www.dndbeyond.com/monsters/296828-zephyros) uses to control the movement of the tower.

Zephyros uses magic to move between levels. A 20-foot-diameter hole in the floor allows access to the first level, the floor of which is 100 feet below. A similarly sized hole in the ceiling leads to the aerie.

#### [](https://www.dndbeyond.com/sources/dnd/skt/a-great-upheaval#SecondFloorTreasure)Treasure

The wooden chest is 9 feet long, 5 feet wide, and 5 feet tall. It contains an assortment of giant-sized robes, a giant pair of sandals, a large electrum comb encrusted with moonstones (worth 750 gp and weighing 25 pounds), and Zephyros’s spellbook. The spellbook weighs 250 pounds has gilded silver covers. It contains all the spells that Zephyros has prepared plus the following additional spells: [arcane eye](https://www.dndbeyond.com/spells/2001-arcane-eye), [continual flame](https://www.dndbeyond.com/spells/2048-continual-flame), [fire shield](https://www.dndbeyond.com/spells/2104-fire-shield), [hypnotic pattern](https://www.dndbeyond.com/spells/2150-hypnotic-pattern), [mage armor](https://www.dndbeyond.com/spells/2172-mage-armor), [mirror image](https://www.dndbeyond.com/spells/2193-mirror-image), [misty step](https://www.dndbeyond.com/spells/2195-misty-step), [modify memory](https://www.dndbeyond.com/spells/2196-modify-memory), [shatter](https://www.dndbeyond.com/spells/2246-shatter), and [slow](https://www.dndbeyond.com/spells/2256-slow).

Zephyros’s library contains more than five hundred research journals that he wrote himself. For the past fifty years, Zephyros has been drifting around the Moonshae Isles and cataloging its many wonders, both magical and mundane. Each book weighs 100 pounds, consolidates a month’s worth of research, and is worth as much as 250 gp.

### [](https://www.dndbeyond.com/sources/dnd/skt/a-great-upheaval#Aerie)Aerie

The highest level of the tower has open archways set into its walls. Four [griffons](https://www.dndbeyond.com/monsters/16913-griffon) have made nests in the aerie, and Zephyros treats them like cats. At any given time, 1d4 of the griffons are present; absent griffons are out hunting and return after 1d4 hours. Griffons that are present attack if they or their nests are disturbed. The griffons’ nests contain no treasure.

# Encounter - Unfriendly Skies

One or both of the following encounters occur while the characters are traveling with Zephyros. If the characters are making the journey on their own, without the cloud giants’ assistance, skip this section and use the [Random Wilderness Encounters](https://www.dndbeyond.com/sources/skt/the-savage-frontier#RandomWildernessEncountersTable) table in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier) to generate overland encounters.

### Day 3: The Howling Hatred

>[!note]+ Read Aloud
>On the third day of your journey, you spot nine very thin and lightly armored humans riding giant vultures. They land atop the cloud, whereupon the humans dismount. All the riders wear steel helms that cover their eyes and resemble stylized bird heads. One of them is equipped with a shoulder bag adorned with a smiling face.

On the third day of the party’s journey, representatives of an evil elemental cult called the Howling Hatred arrive at Zephyros’s tower, hoping to find a powerful cloud giant ally whose goals coincide with those of Yan-C-Bin, the Prince of Evil Air.

The cultists use giant vultures as flying mounts. When they spot the cloud giant’s tower, they investigate. The cultists land outside the tower’s entrance on the first floor. Zephyros is sleeping on the second floor when they arrive and only becomes aware of visitors if the characters wake him or if combat erupts.

The visitors include two [cult fanatics](https://www.dndbeyond.com/monsters/16836-cult-fanatic) (NE male Illuskan humans) and seven [cultists](https://www.dndbeyond.com/monsters/16835-cultist) (NE male and female humans of various ethnicities). The [cultists](https://www.dndbeyond.com/monsters/16835-cultist) try to enter the tower while their nine [giant vultures](https://www.dndbeyond.com/monsters/16897-giant-vulture) remain outside. The vultures allow only members of the cult to ride them, and they attack anyone else who approaches within 5 feet of them. A character who dons a cultist’s costume can, with a successful DC 12 Charisma ([Animal Handling](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check, fool a [giant vulture](https://www.dndbeyond.com/monsters/16897-giant-vulture) into allowing him or her to ride it. The [giant vulture](https://www.dndbeyond.com/monsters/16897-giant-vulture) attacks the character if the check fails.

The [cult fanatics](https://www.dndbeyond.com/monsters/16836-cult-fanatic) are named Amarath and N’von. They speak for the rest of the group and claim to speak on behalf of Yan-C-Bin as well. Amarath and N’von wish to make contact with a cloud giant and have no interest in dealing with anyone else. If the characters get in the way, the [cultists](https://www.dndbeyond.com/monsters/16835-cultist) ignore them and call out for master of the tower. If the characters get pushy or turn violent, the [cultists](https://www.dndbeyond.com/monsters/16835-cultist) attack them.

Amarath carries a magic bag (see “Treasure”) with an [invisible stalker](https://www.dndbeyond.com/monsters/16934-invisible-stalker) inside it. On his first turn in combat, Amarath releases the [invisible stalker](https://www.dndbeyond.com/monsters/16934-invisible-stalker) and commands it to attack the cult’s enemies.

![[beast_cultist_flying.png|500]]

#### Treasure

Amarath’s “smiling bag” is actually a [bag of holding](https://www.dndbeyond.com/magic-items/4581-bag-of-holding). The bag becomes empty once the [invisible stalker](https://www.dndbeyond.com/monsters/16934-invisible-stalker) leaves it.

N’von carries a pouch containing ten pinches of faerie dust. He offers the pouch to Zephyros as a gift (see “Development”).

One pinch of the faerie dust can substitute for the material components of any enchantment spell of 3rd level or lower. The faerie dust has other magical effects as well. If a pinch of faerie dust is sprinkled on a creature, roll percentile dice and consult the Faerie Dust table to determine the effect.

##### Faerie Dust
|d100|Magical Effect|
|---|---|
|01–70|The creature sprinkled with dust gains a flying speed of 60 feet for 10 minutes.|
|71–80|The creature sprinkled with dust must succeed on a DC 11 Constitution saving throw or fall [unconscious](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#UnconsciousCondition) for 1 minute. The creature awakens if it takes damage or if it is shaken or slapped as an action.|
|81–90|The creature sprinkled with dust must succeed on a DC 11 Wisdom saving throw or be affected by a [confusion](https://www.dndbeyond.com/spells/2038-confusion) spell.|
|91–00|The creature sprinkled with dust becomes [invisible](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#InvisibleCondition) for 1 hour. Any equipment it is wearing or carrying is [invisible](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#InvisibleCondition) as long as it is on the creature’s person. The effect on the creature ends if it attacks, deals any damage, or casts a spell.|

#### [](https://www.dndbeyond.com/sources/dnd/skt/a-great-upheaval#TheHowlingHatredDevelopment)Development

If a battle erupts between the characters and the cultists, [Zephyros](https://www.dndbeyond.com/monsters/296828-zephyros) (eccentric wizard that he is) watches the chaos unfold from a safe distance. Only if the characters are near defeat does the cloud giant cast a [mass suggestion](https://www.dndbeyond.com/spells/2184-mass-suggestion) spell on the [cultists](https://www.dndbeyond.com/monsters/16835-cultist) and the [invisible stalker](https://www.dndbeyond.com/monsters/16934-invisible-stalker), urging them to leave at once and never return.

If the characters allow the [cultists](https://www.dndbeyond.com/monsters/16835-cultist) to speak to [Zephyros](https://www.dndbeyond.com/monsters/296828-zephyros), they offer him the pouch of faerie dust as a gift and urge him to help Yan-C-Bin “return the world to its primordial state, as it was at the dawn of history.” The [cultists](https://www.dndbeyond.com/monsters/16835-cultist) are hazy on how this can be achieved and more interested in a yes or no from the giant.

Zephyros accepts whatever counsel the characters wish to offer. Unless the characters advise him to send away the [cultists](https://www.dndbeyond.com/monsters/16835-cultist), Zephyros accepts the cultists’ gift and allows them to remain in his tower while he considers their offer. He then retreats to the second floor and casts [contact other plane](https://www.dndbeyond.com/spells/2045-contact-other-plane) to determine the best course of action. If he fails the spell’s Intelligence saving throw, he remains catatonic until he finishes a long rest. If the save is successful, he determines with the aid of the spell that the cult’s interests are opposed to his own, and politely asks the [cultists](https://www.dndbeyond.com/monsters/16835-cultist) to leave. The cultists grudgingly concede to his request and take their leave, but not before Amarath chastises the cloud giant wizard for his “foolish and shortsighted decision.”

After his business with the [cultists](https://www.dndbeyond.com/monsters/16835-cultist) is concluded, [Zephyros](https://www.dndbeyond.com/monsters/296828-zephyros) feels bad about keeping their gift and gives the pouch of faerie dust to the characters, believing they might get more use out of it than he will.

### Day 10: Operation “Orb Strike”

This encounter occurs on day 10 of the party’s journey and takes place only if the characters are traveling to Bryn Shander or Triboar. The preponderance of giant activity in the North has members of the Lords’ Alliance on edge, and their operatives are gathering information while taking steps to curtail the giants’ advances.

Any character standing guard outside Zephyros’s tower or watching the sky from the tower’s aerie spots danger approaching if his or her passive Wisdom ([Perception](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) score is 15 or higher.

>[!note]+ Read Aloud
>A huge silver dragon glides through the clouds, approaching quickly. As it flies closer, you see a number of armored dwarves clutched in its talons.

A male [adult silver dragon](https://www.dndbeyond.com/monsters/16772-adult-silver-dragon) named Clarion owes a favor to Queen Dagnabbet of Mithral Hall and is transporting a Lords’ Alliance strike team to Zephyros’s tower at her behest. The dragon clutches three shield dwarves in each foreclaw. The dwarves have orders to disable cloud giant strongholds, and they plan to locate and destroy the tower’s [navigation orb](https://www.dndbeyond.com/magic-items/5518-navigation-orb). Neither they nor the dragon know that Zephyros poses no threat to the settlements of the North, nor do they care. They have orders from their queen and a mission to complete, and by Moradin’s beard, they intend to succeed!

Characters who spot the silver dragon have 1 minute to prepare for its arrival. Otherwise, all of the tower’s inhabitants are startled by the sound of the dragon’s flapping wings as he lands on the cloud outside the tower. After dropping off the dwarves, Clarion takes to the air, frightens away the [griffons](https://www.dndbeyond.com/monsters/16913-griffon) in the tower’s aerie, and waits there while the dwarves complete their work.

The [shield dwarves](https://www.dndbeyond.com/monsters/296856-shield-dwarf) are named Daina Ungart, Ildehar Ironfist, Hewen Horn, Voldrik Firehammer, Griswelda Torunn, and Naalt Splintershield. They have the statistics of [veterans](https://www.dndbeyond.com/monsters/17045-veteran), with the following changes:

- The dwarves are lawful good.
- Their speed is 25 feet.
- They have [darkvision](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#Darkvision) out to a range of 60 feet.
- They speak Common and Dwarvish.
- They have advantage on saving throws against poison, and they have resistance to poison damage.
- They wield battleaxes instead of longswords, and handaxes instead of shortswords (the handaxes deal slashing damage instead of piercing damage).
- Each is equipped with a [potion of gaseous form](https://www.dndbeyond.com/magic-items/4705-potion-of-gaseous-form).

The [dwarves](https://www.dndbeyond.com/monsters/296856-shield-dwarf) quaff their [potions of gaseous form](https://www.dndbeyond.com/magic-items/4705-potion-of-gaseous-form) upon landing and make their way into the tower, searching for the [navigation orb](https://www.dndbeyond.com/magic-items/5518-navigation-orb). Realizing that the orb isn’t on the first floor, they fly up to the second floor. Once the orb is in sight, the dwarves revert to their true forms and attack it. [Zephyros](https://www.dndbeyond.com/monsters/296828-zephyros) does his best to protect the orb without harming any of the dwarves, using spells such as [charm person](https://www.dndbeyond.com/spells/2025-charm-person), [Otiluke’s resilient sphere](https://www.dndbeyond.com/spells/2349-otilukes-resilient-sphere), and [mass suggestion](https://www.dndbeyond.com/spells/2184-mass-suggestion) to trap or divert them. Meanwhile, the dragon watches the battle from the aerie and tries to neutralize the cloud giant wizard with its paralyzing breath.

The dragon and the dwarves avoid armed conflict with the characters. If the characters kill one or more of the dwarves or deal damage to the dragon, they are accused of conspiring with giants to bring about the downfall of dwarven civilization in the North. The strike team turns on the party, attempting to knock the characters [unconscious](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#UnconsciousCondition) instead of killing them.

#### [](https://www.dndbeyond.com/sources/dnd/skt/a-great-upheaval#OperationOrbStrikeDevelopment)Development

A character can try to persuade the dragon and the dwarves to end their assault by convincing them that Zephyros means no harm. If the player roleplays well and makes a convincing argument, allow the character to use an action to make a DC 15 Charisma ([Persuasion](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check, with advantage if the character is a member of the Lords’ Alliance, and with disadvantage if one or more members of the strike team are dead. If the check fails, the dwarves say they “can’t take any chances” and press forward with their plan, though the character can try again. If the check succeeds, the dragon and the dwarves call off the attack.

If the dwarves destroy the [navigation orb](https://www.dndbeyond.com/magic-items/5518-navigation-orb), the tower is stranded until Zephyros crafts a replacement (which could take months). Rather than strand the characters in his tower, he helps them return to the surface, points them in the right direction, and bids them farewell before returning to his tower to ponder his options.

If the strike team is thwarted or calls off the mission, the dwarves ask Clarion to fly them back to Mithral Hall. If the dwarves are killed, the dragon returns to Mithral Hall alone. Once the Lords’ Alliance strike team is gone, Zephyros thanks characters who helped defend the tower, mutters something about dragons under his breath, and carries on as though nothing happened.

>[!note]+ CHARACTER ADVANCEMENT
>Characters gain levels in this chapter by completing the goals summarized below:
>- Characters who explore Nightstone and defeat the goblins in the village advance to 2nd level.
>- Characters who deal with the Zhentarim operatives and survive the orc siege (with or without the assistance of the elves of the Ardeep Forest) advance to 3rd level.
>- Characters who survive the perils of the Dripping Caves advance to 4th level, regardless of how many villagers they rescue.
>- Characters advance to 5th level after their encounters with the air cultists and the Lords’ Alliance strike team.
>- The characters should be 5th level by the time they reach Bryn Shander, Goldenfields, or Triboar, as described in [chapter 2](https://www.dndbeyond.com/sources/skt/rumblings).


>
>
# Map
![[013-towerofzephyros.webp]]
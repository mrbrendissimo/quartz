---
tags:
  - Category/Quest
MyContainer:
  - "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
  - "[[2-World/Hubs/Goldenfields.md|Goldenfields]]"
MyCategory:
obsidianUIMode: preview
questObtained:
questStatus: Not Started
questGiver:
questLocationObtained: "[[2-World/Hubs/Goldenfields.md|Goldenfields]]"
questSessionObtained:
questNotes:
questLootAvail:
questLookEarned:
NoteIcon: quest
PromptInfo:
  promptId: GenEncounter
  name: 🍻 Generate Encounter 🛏️
  description: Generate a enocunter.
  author: JoshP
  tags: fantasy, ttrpg
  version: 0.0.1
---



> [!NOTE] Parent Region: `INPUT[inlineListSuggester(optionQuery(#Category/Hub),optionQuery(#Category/Region),optionQuery(#Category/Place),optionQuery(#Category/PointofInterest)):MyContainer]`

> [!column|no-i no-t]
>> [!info|no-title] Map
>> ![[020-skt02-04.webp]]
>
>> [!note|no-title] Town Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, 🏆Quest Info),
>> option(2, 🕵️‍♀️Quest Details),
>> option(3, 📝GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#Quest Info|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Quest Details|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 


> [!NOTE|no-title] 
> ~~~meta-bind
> INPUT[select(
> option(1, 🏡Backstory),
> option(2, 🍎Planning),
> option(3, 🙎‍♂️People),
> class(tabbed)
> )]
> ~~~
>>[!tabbed-box-maxh|div-m]
>>>[!div-m|no-title]
>>> ![[#Backstory|no-h clean]]
>>
>>> [!div-m|no-title]
>>> ![[#Planning|no-h clean]]
>>
>>> [!div-m|no-title]
>>> ![[#People|no-h clean]]



---
# Quest Info

Provide a summary of the quest here. 

- [ ] Obtain the quest
- [ ] Embark on an epic journey
- [ ] Complete the quest
- [ ] Roll in epic loot

# Quest Details


Date Obtained: `INPUT[datePicker:questObtained]` 
Status: `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` 
Quest Giver: `INPUT[suggester(optionQuery(#Category/People)):questGiver]` 
Quest Location: `INPUT[suggester(optionQuery(#Category/Hub)):questLocationObtained]` 
Session Obtained: `INPUT[suggester(optionQuery(#Category/Journal)):questSessionObtained]` 
Available Loot: `INPUT[suggester(optionQuery(#item)):questLootAvail]` 
Acquired Loot: `INPUT[suggester(optionQuery(#item)):questLookEarned]` 

# People

`BUTTON[button_person]` The following people are associated with this quest.

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender", Connected_Groups AS "Associated Group"
FROM "2-World/People"
WHERE contains(char_status, "Alive")
WHERE contains(Connected_Quests, this.file.link)
SORT file.name ASC
```

# GM Notes

### Attack on Goldenfields

>[!NOTE]+ Read Aloud
>A mighty yell shatters the night’s silence. “We’re under attack!” the voice calls out. “To arms! To arms!” Gathering your wits and weapons, you stumble outside the inn. A low mist blankets the quiet gardens to the north and slinks between the rows of darkened longhouses to the south. A small figure stumbles around the corner of the nearest longhouse, loses his balance, and falls. You have never seen such a clumsy, disheveled halfling.

Guh, the self-styled chief of the hill giants, has driven off her female rivals and conquered their husbands. Now, she tasks her mates with collecting food for her voracious appetite. Two of these big dummies, Lob and Ogg, wandered the hills and valleys south of Grudd Haug, the den of Guh’s clan. They eventually blundered into the Forlorn Hills and, a few weeks ago, stumbled upon a gang of bugbears and goblins. The goblinoids told Lob and Ogg about a large farm on the far side of the Dessarin River. It occurred to the hill giants that they should attack it. So, the giants waded across the river and hurled rocks at Goldenfields, pounding its outer wall and alarming its residents. Archers on the wall retaliated with a barrage of arrows. The giants and goblinoids withdrew to nurse their wounds, leaving Goldenfields’ defenders to wonder when the next attack would come. The attack hasn’t changed the mood among the residents, who place great stock in the strength of their outer defenses and militia.

Lob and Ogg spent the next month lost in the hills, trying to find their way back to Grudd Haug. When they got there, they told Guh about the “big farm.” Guh dispatched a horde of hill giants, ogres, bugbears, and goblins to pillage it. With Lob and Ogg leading the way, the horde got lost in the hills and blundered into a copper dragon’s territory. Many giants, ogres, bugbears, and goblins died that day. The survivors fled, only to stumble into an Uthgardt ambush. At that point, it became clear to those who remained alive that Lob and Ogg were poor guides and detrimental to the success of the mission. The bugbears took over from there, leading the remnants of the horde to Goldenfields, with Lob and Ogg bringing up the rear and blaming one another for their misadventures.

The following monsters make it to Goldenfields and participate in the attack:

- Six [hill giants](https://www.dndbeyond.com/monsters/16923-hill-giant), including Lob and Ogg
- Twelve [ogres](https://www.dndbeyond.com/monsters/16969-ogre), six of them fitted with goblin huckers
- Twelve [bugbears](https://www.dndbeyond.com/monsters/16817-bugbear)
- Sixty [goblins](https://www.dndbeyond.com/monsters/16907-goblin), split into two groups of thirty

All of the bugbears, and half of the ogres and goblins, climb over the walls in the dead of night. They slip into the wheat fields in search of food to plunder, not realizing that most of the edible food is stored in cellars under the watch posts along the walls. As the intruders quietly prowl Goldenfields in search of food, the six hill giants stand beyond the wall with open sacks, waiting to catch whatever food the goblins and bugbears toss over the wall. Meanwhile, the remaining six ogres and thirty goblins lurk in the darkness outside the wall.

Luckily for the people of Goldenfields, a half-drunk halfling named [Oren Yogilvy](https://www.dndbeyond.com/monsters/27595-oren-yogilvy) (see [area G8](https://www.dndbeyond.com/sources/dnd/skt/rumblings#G8NorthfurrowsEnd)) spots the monstrous trespassers and sounds the alarm.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#GoldenfieldsBeginningtheEncounter)Beginning the Encounter

The following boxed text assumes that the characters are staying at [[G8. Northfurrow’s End]].

Not long after the initial attack on Goldenfields, the abbot received reports of giant sightings throughout the [[Dessarin Valley]]. He shared these reports with Strog Thunderblade, his Captain of the Guard. Unfortunately, Strog did nothing to prepare for another giant attack. In fact, he never got around to briefing his men or drafting workers or adventurers to help patrol the outer wall, as per the Abbot’s instructions.

Thanks to Strog’s lackluster handling of the situation, the ogres, bugbears, and goblins are able to scale the eastern wall at the point marked X on the map and enter the [[G13. Wheat Fields|wheat fields]] undetected. Once over the wall, they split into three gangs, with two ogres, four bugbears, and ten goblins per gang. The Moon Biters gang reaches the animal pens [[G5. Livestock Fields]] at the same time that the Eye Stabbers reach the town [[G6. Town]]. The Hill Howlers get lost in the wheat field and emerge near a random cluster of grain towers ([[G4. Grain Towers]]. Once they realize their mistake, they head back into the field and make their way toward the abbey [[G7. Harvesthome Abbey]]. [[ Oren Yogilvy]] spots the Eye Stabbers while wandering through town, half-drunk, mulling over lyrics for a new song. Using his powerful set of lungs, he sounds the initial alarm and rushes back toward the inn.

#### Defense of Goldenfields

The guards at the gatehouse ([[G1. Gatehouse]]), on the wall ([[G2. Watch Posts]]), and at the brewery ([[G9. Goldengulp Brewery]]) are too far away to hear Oren’s call to arms, but adventurers in the town, the abbey, or the nearby inn hear him loud and clear, as do various special NPCs. Give each player one of the following NPCs to play during this encounter:

[[Shalvus Martholio]], shepherd and [[Zhentarim]] spy (starts at [[G8. Northfurrow’s End]], inside the inn)

[[Lifferlas]], awakened tree (starts at [[G6. Town]]), in the grove of trees)

[[Zi Liang]], acolyte of Chauntea (starts at [[G7. Harvesthome Abbey]]

[[Miros Xelbrin]], innkeeper (starts at [[G8. Northfurrow’s End]], inside the inn)

[[Naxene Drathkala]], resident mage (starts at [[G8. Northfurrow’s End]], inside the stable house)

[[Oren Yogilvy]], musician (starts at [[G8. Northfurrow’s End]], outside the inn)

Statistics and roleplaying notes for these NPCs appear in [appendix D](https://www.dndbeyond.com/sources/skt/special-npcs#AppendixDSpecialNPCs). How the players run their NPCs during the battle is up to them, but encourage the players to review their NPCs’ ideals, bonds, and flaws. All of these NPCs are familiar with Goldenfields’ defenses and can run to get help, if that’s what the players want them to do. For more information on how to use and run these NPCs, see the “[Special NPCs](https://www.dndbeyond.com/sources/dnd/skt/rumblings#SpecialNPCs)” section at the start of this chapter. If the players try to keep the special NPCs out of the fight, you can endanger them by having one or more groups of monsters threaten the NPCs directly, thereby requiring the player-controlled NPCs to act.

Each gang of monsters is a separate encounter. If the abbey’s bell hasn’t been rung by the time the second gang of goblinoids is defeated, the abbot rings it. (It takes time for the abbot to realize something is amiss and reach the bell in the dead of night.) The ringing bell can be heard for miles and puts all of Goldenfields’ defenses on alert. The bell panics any ogres, bugbears, and goblins that are still inside the compound, and they flee back toward the wall.

During this time, inexplicably, Lob and Ogg decide to climb over the wall and enter the compound rather than flee, while the other four hill giants regroup with the ogres and goblins lurking outside Goldenfields. The giants leave behind their greatclubs, since they can’t climb the walls with their clubs in hand. A handful of guards confront the two foolish giants, but they retreat once Lob and Ogg start breaking off and hurling wall battlements (treat as hurled rocks). The two giants eventually make their way toward the abbey ([area G7](https://www.dndbeyond.com/sources/dnd/skt/rumblings#G7HarvesthomeAbbey)). If either giant is reduced to 15 hit points or fewer, he surrenders (see “[Development](https://www.dndbeyond.com/sources/dnd/skt/rumblings#AttackonGoldenfieldsDevelopment)”).

If forced into melee combat, an unarmed hill giant can use its action to make two unarmed attacks. Replace the giant’s greatclub attack with the following attack option:

**_Unarmed Attack._** _Melee Weapon Attack:_ +8 to hit, reach 10 ft., one target. _Hit:_ 12 (3d4 + 5) bludgeoning damage.

fter the characters deal with the threats inside the walls, townsfolk emerge from their longhouses and begin to scour the fields for stray threats. Characters who join the search find trails that lead back to the wall. By this time, the sky to the east has lightened enough to reveal the presence of giants, ogres, and goblins outside the wall. The invaders close to within 120 feet of the wall and begin hurling rocks and goblins.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#GoblinHuckers)Goblin Huckers

The six ogres that remain outside Goldenfields wear hobgoblin inventions called goblin huckers. Each of these contraptions is essentially a portable trebuchet strapped to a leather harness. The contraption rests on an ogre’s back and shoulders, and despite its cumbersome appearance, it doesn’t inhibit the wearer’s mobility or fighting ability. It takes 10 minutes for someone else to attach or remove the elaborate harness, or 1d6 hours if an ogre attempts to do so unassisted. The contraption is built for ogres specifically. A dwarf or similarly built humanoid that is magically transformed to Large size can don or doff a goblin hucker in 10 minutes.

The sling of the trebuchet is big enough to hurl a rock, a flaming cask of pitch, or a similarly sized projectile — but the contraption was designed to fling goblins. A goblin used as a projectile typically wears a spiked helmet, so that it deals piercing damage to the target on impact. The thirty goblins outside Goldenfields are equipped with helmets. A goblin rarely survives the experience of being hurled through the air in this fashion. The goblins here stand ready to be flung at enemies on the wall, while the ogres position themselves 300 feet away from their targets.

The wearer of a goblin hucker launches its payload in a high arc, so it can hit targets behind cover. Loading the sling is an action that the contraption’s wearer can’t perform. A goblin willing to serve as a living projectile can load itself, if necessary. The ogre must then use an action to aim the weapon and pull the cord that releases the sling and hurls the projectile through the air.

_**Goblin Projectile.** Ranged Weapon Attack:_ +3 to hit, range 150/600 ft. (can’t hit targets within 30 feet of the hucker), one target. _Hit:_ 5 (2d4) bludgeoning damage, or 10 (4d4) piercing damage if the projectile is wearing a spiked helmet. _Hit or Miss:_ The goblin projectile takes 1d6 bludgeoning damage per 10 feet it travels through the air (maximum 20d6).

#### Treasure

Each hill giant carries a sack that holds 1d4 mundane items, determined by rolling on the [Items in a Giant’s Bag](https://www.dndbeyond.com/sources/skt/introduction#ItemsinaGiantsBag) table in the [introduction](https://www.dndbeyond.com/sources/skt/introduction), and 1d4 - 1 art objects worth 250 gp each (roll on the appropriate [Art Objects](https://www.dndbeyond.com/sources/dmg/treasure#ArtObjects) table in [chapter 7](https://www.dndbeyond.com/sources/dmg/treasure) of the [Dungeon Master’s Guide](https://www.dndbeyond.com/sources/dmg)). Each bugbear carries a pouch that holds 1d6 gemstones (worth 10 gp each), and each goblin carries 1d6 cp in a pouch as well as various worthless belongings (necklaces made of woven dwarf beards and strung with halfling ears, bowls made from human skulls, and the like). The ogres have no treasure.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#AttackonGoldenfieldsDevelopment)Development

The monsters inside the compound are smart enough to realize that they can’t survive in Goldenfields for long after an alarm has sounded. Those that escape rejoin their comrades waiting outside the wall. Lob and Ogg are the exceptions; more afraid of Guh than of the Goldenfields defenders, they hate the thought of returning to their chief without a mountain of food. But neither giant wants to die, and each surrenders if reduced to 15 hit points or fewer, falling to the ground and beginning to sob like a big baby. If questioned, Lob or Ogg responds by blubbering incoherently. A successful DC 15 Charisma ([Intimidation](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check pries the following information out of a defeated but conscious hill giant:

- “Guh want food.”
- “Me get food for Guh.”
- “Guh big. Real big. Bigger than me.”
- “Grudd Haug. Home.”

Characters who successfully intimidate one or both giants can command them to lead the way to Grudd Haug. But because neither giant has a good sense of direction, any such expedition is doomed. The hill giants become disoriented while leading the party into the Forlorn Hills east of Goldenfields. Stupid beyond belief, Lob and Ogg are unable to find their way back to Grudd Haug no matter how strongly the characters motivate them.

Captured monsters that are left to the tender mercies of the Goldenfields defenders are put to death, by order of Captain Strog Thunderblade. The captain then takes credit for defeating the monstrous horde that attacked Goldenfields. The abbot, being much more sensible, thanks the adventurers profusely and makes sure they’re cited for their heroics and well supplied when the time comes for them to leave. If the characters call for Strog’s resignation, the abbot vows to give their recommendation serious thought.

Whether or not the characters thwart the attack on Goldenfields, they gain special quests and rewards based on which NPCs survived the battle.


## prompt: Encounter Name
Prompt: Generate a random encounter for Dungeons and Dragons 5e for a party of 5 level 5 players. The theme of the encounter should be appropriate to the {{context}}. 

The encounter should be listed in the exact format provided below if there is an encounter in the room. Remove and or change the monsters used if appropriate. Always write the monsters name as a singular monster, plurals are not supported by the Initiative Tracker plugin. The monsters name must match exactly what is listed in the Monster Manual or rules. Do not add any additional text to the monsters name within the encounter code block. The encounter code block should be at the bottom with all descriptive text above it. 

```encounter
name: Example
creatures:
 - 6: Hill Giant
 - 12: Ogre
 - 12: Bugbear
 - 60: Goblin      
```


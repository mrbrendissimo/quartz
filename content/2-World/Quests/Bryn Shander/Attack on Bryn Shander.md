---
tags:
  - Category/Quest
MyContainer:
  - "[[2-World/Hubs/Bryn Shander.md|Bryn Shander]]"
  - "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
MyCategory:
obsidianUIMode: preview
questObtained:
questStatus: Not Started
questGiver:
questLocationObtained: "[[2-World/Hubs/Bryn Shander.md|Bryn Shander]]"
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
>> ![[tc_bryn_shander_watchtower.jpg|500]]
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

### Attack on Bryn Shander

Twelve [[frost-giant-variant-skt|Frost Giant]] come to Bryn Shander looking for [[2-World/People/Bryn Shander/Artus Cimber]] and the [[test_Ring of Winter]]. **Their leader, Drufi**, has two [[winter-wolf-xmm|Winter Wolf]] traveling with her. While nine of her giants encircle the town, Drufi, the wolves, and two other frost giants (Drufi’s bodyguards, one male and one female) stride boldly toward the southwest gate, demanding to parlay with whoever’s in charge of the town. Sheriff [[Markham Southwell]] leads Town Speaker [[Duvessa Shane]] to the gatehouse to speak with the angry giant. [[Augrek Brighthelm]] is already there.

#### Beginning the Encounter

The characters are in Bryn Shander when the attack begins, either together in one place or scattered throughout the town. Read or paraphrase the following boxed text when the attack begins.

> [!warning]+ Read when the attack begins
> Another dreadfully cold day in Icewind Dale has you bundled up in your warmest furs. Bryn Shander’s market square bustles with knucklehead trout fishers selling their finest scrimshaw to traders from the south, while other common folk warm their hands and faces by small campfires. Everywhere across town, people are trudging through snow-covered streets on errands. The town’s outer walls block the worst of the wind, but not all of it. A sudden blast occasionally catches everyone by surprise, causing shivers and grumbling all around.
The mood of the town changes abruptly. Something is amiss. Pedestrians are vacating the square with great haste, disappearing into their hovels. As spear-toting guards with grim faces move with purpose toward the southwest gate, you hear a booming voice from that direction as it calls out, “Surrender Artus Cimber or die!”
> 

The frost giants believe that a male human named [[2-World/People/Bryn Shander/Artus Cimber]] is holed up in Bryn Shander, and Drufi demands that the town hand over Artus and all of his possessions to her immediately. Duvessa and Markham know of no such person, and no such person steps forward.

Drufi carries a horn made from a mammoth’s tusk and can blow it as an action. The horn can be heard out to a range of one mile. If her demands aren’t met immediately, Drufi uses the horn to signal the other frost giants, who advance to within 100 feet of the town and begin hurling rocks over the walls, not targeting anyone or anything specifically but looking to cause widespread panic. As townsfolk take cover, Drufi and her two giant bodyguards try to break down the southwest gate and fight their way inside. While this is happening, a young man named Sirac at the House of the Triad learns what the giants are after and realizes he might be able to save the town.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#DefenseofBrynShander)Defense of Bryn Shander

The threat of a full-scale frost giant attack throws the town of Bryn Shander into chaos. Many guards abandon their posts, leaving the defense of the southwest gatehouse to the adventurers. The characters can either confront the giants and the winter wolves that are breaking through the southwest gate or deal with the rock-hurling giants as they see fit. Once the characters choose their enemies, assume that Bryn Shander’s militia is dealing with the other threats.

Give each player one of the following NPCs to play during this encounter:

[[Augrek Brighthelm]], a sheriff’s deputy (starts at [[[B1. Outer Gatess]]], southwest gate)

[[Sirac of Suzail]], an acolyte of Torm (starts at [[B4. House of the Triad]]

[[Duvessa Shane]], the town speaker (starts at [[B1. Outer Gatess]], southwest gate)

[[Markham Southwell]], the sheriff (starts at [[area B1]], southwest gate)

[[Beldora]], a Harper spy (starts at [[B7. Marketplace]]

[[Sir Baric Nylef]], a knight of Tyr (starts at [[B8. Kelvin’s Comfort]]

Statistics and roleplaying notes for these NPCs appear in [appendix D](https://www.dndbeyond.com/sources/skt/special-npcs#AppendixDSpecialNPCs). How the players run their NPCs during the battle is up to them, but encourage the players to review their NPCs’ ideals, bonds, and flaws. For more information on how to use and run these NPCs, see the “[Special NPCs](https://www.dndbeyond.com/sources/dnd/skt/rumblings#SpecialNPCs)” section at the start of this chapter.

If the players try to keep the special NPCs out of the fight, you can endanger them by having one or more giants break through the wall, storm the town, and threaten the NPCs directly, thereby requiring the players’ NPCs to act.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#AttackonBrynShanderTreasure)Treasure

Drufi’s ivory horn is worth 750 gp intact. The frost giant also has fifteen 100 gp gemstones set into her helm that can be pried loose. Each other frost giant carries a sack that holds 1d6 mundane items, determined by rolling on the [Items in a Giant’s Bag](https://www.dndbeyond.com/sources/skt/introduction#ItemsinaGiantsBag) table in the [introduction](https://www.dndbeyond.com/sources/skt/introduction), as well as 1d4 art objects worth 25 gp each (roll on the appropriate [Art Objects](https://www.dndbeyond.com/sources/dmg/treasure#ArtObjects) table in [chapter 7](https://www.dndbeyond.com/sources/dmg/treasure) of the [Dungeon Master’s Guide](https://www.dndbeyond.com/sources/dmg)). The winter wolves have no treasure.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#AttackonBrynShanderDevelopment)Development

If the characters and their allies defeat Drufi, her two frost giant bodyguards, and her two winter wolves, the remaining frost giants abandon their assault on Bryn Shander and retreat westward, toward the Sea of Moving Ice, where a giant longship waits to transport them to Svardborg (see chapter 7, “[Berg of the Frost Giants](https://www.dndbeyond.com/sources/skt/berg-of-the-frost-giants)”). They don’t remain there long before Jarl Storvald sends them back out in search of [[2-World/People/Bryn Shander/Artus Cimber]].

Drufi won’t leave Bryn Shander until she has either the _Ring of Winter_ or knowledge of its exact whereabouts, so characters will probably have to kill her.

Once the characters defeat the frost giants, they gain special quests and rewards based on which NPCs survived the battle.


## prompt: Attack on Bryn Shander
Prompt: Generate a random encounter for Dungeons and Dragons 5e for a party of 5 level 5 players. The theme of the encounter should be appropriate to the {{context}}. 

The encounter should be listed in the exact format provided below if there is an encounter in the room. Remove and or change the monsters used if appropriate. Always write the monsters name as a singular monster, plurals are not supported by the Initiative Tracker plugin. The monsters name must match exactly what is listed in the Monster Manual or rules. Do not add any additional text to the monsters name within the encounter code block. The encounter code block should be at the bottom with all descriptive text above it. 

```encounter
name: Attack on Bryn Shander
creatures:
 - 3: Frost Giant (variant)
 - 2: Winter Wolf
```
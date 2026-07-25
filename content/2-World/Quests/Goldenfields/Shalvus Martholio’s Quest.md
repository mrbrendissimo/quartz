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
questGiver: "[[2-World/People/Goldenfields/Shalvus Martholio.md|Shalvus Martholio]]"
questLocationObtained: "[[2-World/Hubs/Goldenfields.md|Goldenfields]]"
questSessionObtained:
questNotes:
questLootAvail:
questLookEarned:
NoteIcon: quest
---



> [!NOTE] Parent Region: `INPUT[inlineListSuggester(optionQuery(#Category/Hub),optionQuery(#Category/Region),optionQuery(#Category/Place),optionQuery(#Category/PointofInterest)):MyContainer]`

> [!column|no-i no-t]
>> [!info|no-title] Map
>> ![[Pasted image 20250427093259.png]]
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

#### Shalvus Martholio’s Quest

[[Shalvus Martholio]] asks the party to escort him overland to [[Bargewright Inn]] so that he can report everything that has happened to his boss, Nalaskur.

After making his report, Shalvus takes his leave and shacks up with some friends in Bargewright Inn until Nalaskur gives him a new assignment. Grateful for their assistance, Nalaskur offers the characters a warm dinner and clean beds for the night, free of charge. The next morning, he asks the characters to accompany a beer wagon to the [[Mornbryn’s Shield|Troll in Flames]], a tavern in the village of [[Mornbryn’s Shield]]. Two [draft horses](https://www.dndbeyond.com/monsters/16844-draft-horse) pull the wagon, which has a pair of drivers named Jostin and Lessilar (N male Illuskan human [thugs](https://www.dndbeyond.com/monsters/17035-thug)). They take turns at the reins.

If the delivery is made, the characters pass Nalaskur’s test. Unless they do something to turn [[Zhentarim|The Black Network]] against them, the characters receive an anonymous bundle from the Zhentarim the next time they visit Bargewright Inn, Everlund, Mirabar, Silverymoon, Neverwinter, Waterdeep, or Yartar (all of which have a strong Zhentarim presence). The bundle contains a block of excellent cheese wrapped in silk, a black bottle of “Old Bargewright” wine, and a folded piece of parchment on which are written the following words:

>[!NOTE]+ Read Aloud
>_Zira_
>_The Happy Cow_
>_Daggerford_

Any character who has spent time in [[Daggerford]] can, with a successful DC 10 Intelligence check, recall that the [[Daggerford|Happy Cow]] is a halfling-run tavern in town. If the adventurers visit the tavern, a female [adult bronze dragon](https://www.dndbeyond.com/monsters/16767-adult-bronze-dragon) in half-elf form buys them a round of drinks. The dragon, Zirazylym (“Zira” for short), is on [[Zhentarim|The Black Network's]] payroll.

_**Treasure.**_ If the characters seem nice, Zira grants them a [special favor](https://www.dndbeyond.com/sources/dmg/other-rewards#SpecialFavors) (see the “[Marks of Prestige](https://www.dndbeyond.com/sources/dmg/other-rewards#MarksofPrestige)” section in [chapter 7](https://www.dndbeyond.com/sources/dmg/other-rewards) of the [Dungeon Master’s Guide](https://www.dndbeyond.com/sources/dmg)). When they call in the favor, Zira does her best to help them, though she will not cause direct harm to others or violate local laws. She tries to hide the fact that she’s a dragon, but if the characters need swift transportation to some far-flung destination, she offers to fly them there. She can also hook them up with a [spell scroll](https://www.dndbeyond.com/magic-items/5418-spell-scroll) containing any one spell of 5th level or lower.
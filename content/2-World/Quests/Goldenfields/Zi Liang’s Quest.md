---
tags:
  - Category/Quest
MyContainer: "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
MyCategory:
obsidianUIMode: preview
questObtained:
questStatus: Not Started
questGiver: "[[2-World/People/Goldenfields/Zi Liang.md|Zi Liang]]"
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
In addition to being an acolyte of Chauntea and an Emerald Enclave sympathizer, [Zi](https://www.dndbeyond.com/monsters/27585-zi-liang) is the beneficiary of a considerable inheritance from her parents, who traded in silk, whale oil, fine glass, maps, and other commodities. They were based in Baldur’s Gate but owned several businesses in Waterdeep.

_**Treasure.**_ Zi gives the characters a black pearl pendant (worth 750 gp) that she keeps hidden among her belongings and tells them to bring it to Cauldar Marskyl (LG male Illuskan human [commoner](https://www.dndbeyond.com/monsters/16829-commoner)), the head butler of House Thann in Waterdeep, where he will give them a gift in exchange.

House Thann is one of Waterdeep’s leading vintners, and although Cauldar is elderly and forgetful, he recalls with perfect clarity that the Thann family and Zi’s family are allies. He has been entrusted with some items that once belonged to Zi’s parents, and though Zi is now old enough to have them, she has no immediate need of them and prefers an ascetic lifestyle. If the characters show Cauldar the pendant, he understands that Zi has bequeathed her inheritance to them. He sends servants to the attic to retrieve an old wooden trunk and bring it to the characters, then unlocks it with a key and lets them claim the two magic items inside. Roll on [Magic Item Table C](https://www.dndbeyond.com/sources/dmg/treasure#MagicItemTableC) in [chapter 7](https://www.dndbeyond.com/sources/dmg/treasure) of the [Dungeon Master’s Guide](https://www.dndbeyond.com/sources/dmg) to determine each item. Cauldar offers to keep Zi’s pendant and see it safely returned to her, but he doesn’t protest if the characters insist on keeping it.



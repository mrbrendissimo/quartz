---
tags:
  - Category/Quest
MyContainer:
  - "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
  - "[[2-World/Hubs/Triboar.md|Triboar]]"
MyCategory:
obsidianUIMode: preview
questObtained:
questStatus: Not Started
questGiver: "[[2-World/People/Triboar/Ghelryn Foehammer.md|Ghelryn Foehammer]]"
questLocationObtained: "[[2-World/Hubs/Triboar.md|Triboar]]"
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

# GM Notes

As a reward for their efforts, [Ghelryn](https://www.dndbeyond.com/monsters/27618-ghelryn-foehammer) writes the characters a letter of recommendation (see the “[Marks of Prestige](https://www.dndbeyond.com/sources/dmg/other-rewards#MarksofPrestige)” section in [chapter 7](https://www.dndbeyond.com/sources/dmg/treasure) of the [Dungeon Master’s Guide](https://www.dndbeyond.com/sources/dmg)) and suggests they present it to King Morinn or Queen Tithmel should they find themselves in [[Citadel Felbarr]]. See the “[Citadel Felbarr](https://www.dndbeyond.com/sources/skt/the-savage-frontier#CitadelFelbarr)” section in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier) for more information on the king and queen.

_**Treasure.**_ If the characters pay a visit to Citadel Felbarr and show Ghelryn’s letter to King Morinn and Queen Tithmel, the royal couple ask about Ghelryn’s well-being, commend the party’s devotion to ending the giant threat, and award the characters a special gift to help them in their war on giants: two [figurines of wondrous power (golden lions)](https://www.dndbeyond.com/magic-items/4832-figurine-of-wondrous-power-golden-lions).


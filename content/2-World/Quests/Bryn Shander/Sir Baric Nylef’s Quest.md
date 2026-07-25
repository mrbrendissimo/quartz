---
tags:
  - Category/Quest
MyContainer:
  - "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
  - "[[2-World/Hubs/Bryn Shander.md|Bryn Shander]]"
MyCategory:
obsidianUIMode: preview
questObtained:
questStatus: Not Started
questGiver: "[[2-World/People/Bryn Shander/Sir Baric Nylef.md|Sir Baric Nylef]]"
questLocationObtained: "[[2-World/Hubs/Bryn Shander.md|Bryn Shander]]"
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

[Sir Baric](https://www.dndbeyond.com/monsters/27577-sir-baric-nylef) is determined to find the Weevil. At this point, however, he fears that the trail has gone cold. He plans to remain in Bryn Shander only a couple more days before searching elsewhere, and he doesn’t want to waste the characters’ time in what could end up being a futile hunt for the criminal. Baric believes it’s more important to keep the Order of the Gauntlet apprised of his whereabouts and intentions, so he asks the characters to locate another member of the order and report on Sir Baric’s status. He suggests that they seek out Sir Lanniver Strayl, a devout follower of Tyr who lives in Neverwinter.

Sir Lanniver (LG male Tethyrian human [knight](https://www.dndbeyond.com/monsters/16938-knight) wearing a [cloak of protection](https://www.dndbeyond.com/magic-items/4607-cloak-of-protection)) is grooming his [warhorse](https://www.dndbeyond.com/monsters/17049-warhorse) when the party arrives. Though he is dismayed to learn about the attack on Bryn Shander, he’s relieved to find out that his friend, Sir Baric, is alive and well. Characters who succeed on a DC 10 Wisdom ([Insight](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check notice that Sir Lanniver is deeply troubled. If they pry into his affairs, Sir Lanniver reveals that he’s concerned about another member of the Order of the Gauntlet named Dannika Zarrn, a knight of Helm who has joined a splinter faction of the Order of the Gauntlet called the Order of the Gilded Eye. Sir Lanniver provides the following information about the organization if the characters seem interested in learning more.

- The Gilded Eye has taken root in Helm’s Hold, a monastery south of Neverwinter.
- The Gilded Eye believes that demons and their vile worshipers are spreading corruption throughout the North.
- Gilded Eye inquisitors have taken their worship of Helm to extremes and are determined to destroy anyone they believe is under the demons’ sway, as well as anyone who challenges the edicts or their beliefs.

Sir Lanniver has no quest for the characters but warns them to be careful when visiting [Helm’s Hold](https://www.dndbeyond.com/sources/skt/the-savage-frontier#HelmsHold). See [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier) for more information on this location.

_**Treasure.**_ If the party includes a member of the Order of the Gauntlet (or a character with a strong commitment to stamping out evil), Sir Lanniver gives that party member his [cloak of protection](https://www.dndbeyond.com/magic-items/4607-cloak-of-protection) as a gift.

# Quest Details


Date Obtained: `INPUT[datePicker:questObtained]` 
Status: `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` 
Quest Giver: `INPUT[suggester(optionQuery(#Category/People)):questGiver]` 
Quest Location: `INPUT[suggester(optionQuery(#Category/Hub)):questLocationObtained]` 
Session Obtained: `INPUT[suggester(optionQuery(#Category/Journal)):questSessionObtained]` 
Available Loot: `INPUT[suggester(optionQuery(#item)):questLootAvail]` 
Acquired Loot: `INPUT[suggester(optionQuery(#item)):questLookEarned]` 

# GM Notes

Make notes of what you need to track in the region here. 

# People

`BUTTON[button_person]` The following people are associated with this quest.

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender", Connected_Groups AS "Associated Group"
FROM "2-World/People"
WHERE contains(char_status, "Alive")
WHERE contains(Connected_Quests, this.file.link)
SORT file.name ASC
```





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
questGiver: "[[2-World/People/Bryn Shander/Markham Southwell.md|Markham Southwell]]"
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

### Markham Southwell’s Quest

The sheriff asks the characters to patrol Icewind Dale and return at once if they see further evidence of giant activity in the region. If the characters accept the quest, Southwell deputizes them and gives them three weeks’ worth of provisions, as well as a signed letter attesting that they are acting on his behalf. Characters can present the letter to the town speaker of any other Ten-Towns settlement and expect to receive free room and board.

You can plan encounters as the characters explore Icewind Dale using the [random encounter table](https://www.dndbeyond.com/sources/skt/the-savage-frontier#RandomEncountersinIcewindDale) in the “[Icewind Dale](https://www.dndbeyond.com/sources/skt/the-savage-frontier#IcewindDale)” section in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier). After encountering one or more frost giants, they can return to Bryn Shander and report to the sheriff. If they return with the heads of one or more slain giants, Sheriff Southwell rewards each of them with the title “Defender of Icewind Dale” and spreads news of the party’s heroism throughout Ten-Towns. As long as the characters do nothing to sully their reputations, Ten-Towners are friendly toward them and extend them every courtesy.

Shortly after the characters earn their new titles, they are approached by a pair of freelance bounty hunters named Sorelisa Zandra (N female Tethyrian human [spy](https://www.dndbeyond.com/monsters/17021-spy)) and Naeremos (N male Illuskan human [thug](https://www.dndbeyond.com/monsters/17035-thug)). The bounty hunters wear thick cloaks over their armor, and Naeremos is missing his left arm (which was torn off by a troll).

Although they claim to work for the government of Mirabar, Sorelisa and Naeremos are actually working for the Zhentarim. They are searching for a dwarf fugitive known as the Weevil, who is wanted for banditry. Sorelisa shows the characters a crude sketch of the Weevil (a dark-haired dwarf with a wicked gleam in his eyes) and asks them if they know his whereabouts, while failing to mention that the city of Mirabar has placed a 5,000 gp bounty on the Weevil’s head.

The Zhentarim wants to protect and recruit the Weevil, not turn him over to the Mirabar authorities. Zhentarim operatives stationed in various cities of the North have seen neither hide nor hair of him, leading Sorelisa to suspect that the Weevil is hiding in one of the smaller settlements. Sorelisa promises that if the characters capture the Weevil and deliver him to her and Naeremos alive, she will match Mirabar’s bounty, offering the party a cache of gemstones as payment (see “Treasure”).

See the “[Xantharl’s Keep](https://www.dndbeyond.com/sources/skt/the-savage-frontier#XantharlsKeep)” section in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier) for more information on the Weevil and his current whereabouts.

_**Treasure.**_ Sorelisa and Naeremos share a room in Geldenstag’s Rest ([area B14](https://www.dndbeyond.com/sources/dnd/skt/rumblings#B14GeldenstagsRest)). A hidden compartment in one wall holds a fat leather pouch containing 10 500 gp gemstones. A thorough search of the room accompanied by a successful DC 17 Wisdom ([Perception](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check reveals the hidden compartment, which is not trapped.
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





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
questGiver: "[[2-World/People/Triboar/Darathra Shendrel.md|Darathra Shendrel]]"
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

[Darathra](https://www.dndbeyond.com/monsters/27597-darathra-shendrel) doesn’t have much contact with her fellow Harpers, but it strikes her as odd that fire giants would make it this far into the [[Dessarin Valley]] without her receiving some kind of warning. She wants to make sure her organization is aware of the gravity of the situation. She gives the characters a platinum badge (worth 50 gp) bearing the Triboar insignia (three boars charging forward) and urges the characters to travel east along the [[Evermoor Way]], visit Danivarr’s House in [[Everlund]], and give the badge to Dral Thelev, the one-eyed half-orc proprietor.

If the characters follow Darathra’s instructions, Dral pockets the badge, uncorks a flask of elven wine that he claims is Silverymoon’s finest, and pours its contents into small wooden cups — one per character. Characters who take even the smallest drink of the wine are teleported to a parlor in the heart of Moongleam Tower, [[the Harpers]]’ stronghold in [[Everlund]]. Dral explains how the magic of the elixir works after one party member takes a sip and disappears, expecting that the others will want to follow.

The parlor in Moongleam Tower contains austere furnishings and a dozen harmless, domesticated [tressym](https://www.dndbeyond.com/monsters/17353-tressym) (see [appendix C](https://www.dndbeyond.com/sources/skt/creatures#Tressym)) behaving like house cats. A silent [alarm](https://www.dndbeyond.com/spells/1991-alarm) spell notifies Krowen Valharrow, the tower’s resident archmage, of the party’s arrival. The dotty old wizard enters the parlor shortly after the characters appear, greets them warmly, and grants them free access to a secret network of teleportation circles until, as he puts it, “the Harpers decide otherwise” (see the “[Inner Circles](https://www.dndbeyond.com/sources/skt/the-savage-frontier#InnerCircles)” section in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier)).

_**Treasure.**_ After showing them the teleportation circle in Moongleam Tower, Krowen gives the adventurers a small wooden coffer that Darathra sent him for his birthday a few years back. The coffer’s interior space is divided into six compartments, each of which contains a rolled-up [spell scroll](https://www.dndbeyond.com/magic-items/5418-spell-scroll). The spells written on the scrolls are [dispel magic](https://www.dndbeyond.com/spells/2072-dispel-magic), [fly](https://www.dndbeyond.com/spells/2111-fly), [magic weapon](https://www.dndbeyond.com/spells/2178-magic-weapon), [sending](https://www.dndbeyond.com/spells/2243-sending), [tongues](https://www.dndbeyond.com/spells/2281-tongues), and [water breathing](https://www.dndbeyond.com/spells/2297-water-breathing). (If the characters meet Krowen in Everlund but are not engaged in Darathra’s quest, Krowen does not provide the scrolls.)



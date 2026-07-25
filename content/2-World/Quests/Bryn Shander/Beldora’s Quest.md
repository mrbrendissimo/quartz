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
questGiver: "[[2-World/People/Bryn Shander/Beldora.md|Beldora]]"
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

# GM Notes


[Beldora](https://www.dndbeyond.com/monsters/27575-beldora) urges the characters to head southwest and take Ten Trail through the mountains to the mining settlement of Hundelstone. She suggests they make contact with a gnome named Thwip Ironbottom, who lives there year-round. If one or more of the party members are Harpers, she tells them that Thwip serves as the organization’s eyes and ears in Hundelstone. Beldora uses her [sending stone](https://www.dndbeyond.com/magic-items/5402-sending-stones) to inform Thwip that the characters are coming.

_**Treasure.**_ Upon the characters’ arrival, Thwip gives them a gift: a Tiny clockwork dog made of copper and tin, along with a copper wind-up key. A character must use the key and an action to wind the dog, after which it follows that character for 12 hours. At the end of that duration, the clockwork dog stops until wound again. The dog has AC 5, 1 hit point, and a walking speed of 30 feet.

_**Development.**_ When the heroes are ready to leave Hundelstone, Thwip urges them to visit Everlund and seek out Krowen Valharrow, a Harper wizard who resides at Moongleam Tower (see the “[Inner Circles](https://www.dndbeyond.com/sources/skt/the-savage-frontier#InnerCircles)” section in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier)). The gnome describes Krowen as a powerful wizard known to sponsor adventurers.
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





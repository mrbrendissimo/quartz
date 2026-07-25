---
MyContainer:
  - "[[2-World/Regions/Faerûn.md|Faerûn]]"
  - "[[Beldora|Beldora]]"
MyCategory:
tags:
  - Category/Item
obsidianUIMode: preview
aliases:
  - ItemOtherName
Connected_Quests:
  - "[[z_Templates/World Builder Templates/Template-Quest.md|Template-Quest]]"
Connected_Groups:
  - "[[z_Templates/World Builder Templates/Template-Group.md|Template-Group]]"
---



> [!NOTE|div-m] Parent Location: `INPUT[inlineListSuggester(optionQuery(#Category/Quest),optionQuery(#Category/People),optionQuery(#Category/Group),optionQuery(#Category/Place),optionQuery(#Category/PointofInterest)):MyContainer]`

> [!column|no-i no-t]
>> [!div-m|no-title]
>>
>
>> [!div-m|no-title] Place Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️Description),
>> option(2, ⚔️Features),
>> option(3, 🔗Connections),
>> option(4, 📝GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#Description|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#Features|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#Connections|no-h clean]]
>>> 
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 

# Sending Stones
*Wondrous item, uncommon*  
![](/3-Mechanics/CLI/items/img/sending-stones.webp#right)


Sending Stones come in pairs, with each stone carved to match the other so the pairing is easily recognized. While you touch one stone, you can cast [Sending](/3-Mechanics/CLI/spells/sending-xphb.md) from it. The target is the bearer of the other stone. If no creature bears the other stone, you know that fact as soon as you use the stone, and you don't cast the spell.

Once Sending is cast using either stone, the stones can't be used again until the next dawn. If one of the stones in a pair is destroyed, the other one becomes nonmagical.

*Source: Dungeon Master's Guide (2024) p. 303. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*
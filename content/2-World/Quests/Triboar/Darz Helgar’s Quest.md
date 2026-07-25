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
questGiver: "[[2-World/People/Triboar/Darz Helgar.md|Darz Helgar]]"
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

[Darz](https://www.dndbeyond.com/monsters/27602-darz-helgar) relates to the characters that he was recently visited by an old acquaintance, a merchant from Mirabar, with an interesting tale to tell. The merchant saw a dwarf cleaning stables in Xantharl’s Keep, a fortified village on the Long Road, and later recognized him from a wanted poster he saw while traveling south through Longsaddle. The merchant is sure that the dwarf he saw is a wanted brigand known as the Weevil; according to the wanted poster, whoever delivers him alive to the authorities in Mirabar can collect a reward of 5,000 gp.

Darz briefly entertained the idea of going after the Weevil himself, but then admitted to himself that he’s too old for such things. Passing this information along to the characters is his way of thanking them for their help during the attack.

_**Development.**_ If the characters head to Xantharl’s Keep, they can catch the Weevil and turn him over to the Axe of Mirabar. See the “[Xantharl’s Keep](https://www.dndbeyond.com/sources/skt/the-savage-frontier#XantharlsKeep)” section in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier) for more information.
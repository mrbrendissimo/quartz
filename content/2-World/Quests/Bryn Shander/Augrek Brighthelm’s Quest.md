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
questGiver: "[[2-World/People/Bryn Shander/Augrek Brighthelm.md|Augrek Brighthelm]]"
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

#### Augrek Brighthelm’s Quest

Hoping to win favor with [[Markham Southwell]] but unwilling to leave her post, Augrek asks the characters to meet with one or more representatives of the Brighthelm clan in Ironmaster and ask her clanfolk to send reinforcements to Bryn Shander. She warns the characters that the dwarves of Ironmaster don’t allow non-dwarves inside their lands. But, she says, if the characters travel toward Ironmaster, stand next to one of its menhirs, and wait, some dwarves will eventually approach them. If the characters announce that they’ve come on behalf of Augrek, one of her older cousins, Gwert Brighthelm (LN male dwarf [noble](https://www.dndbeyond.com/monsters/16966-noble) armed with a warhammer instead of a rapier), will be summoned to hear what the characters have to say. Gwert promises to take Augrek’s request to the clan elders.

_**Treasure.**_ At the end of the conversation, Gwert gives each character a 100 gp gemstone as payment for delivering Augrek’s message.

_**Development.**_ If the characters aren’t sure where to go next, Gwert suggests that they visit Dasharra Keldabar, a griffon rider and trainer living in the village of Fireshear, and use the gemstones to pay her to train them to ride griffons. (The gemstones aren’t enough to pay for the training, but Gwert doesn’t know this.) For more information on [Fireshear](https://www.dndbeyond.com/sources/skt/the-savage-frontier#Fireshear) and [Ironmaster](https://www.dndbeyond.com/sources/skt/the-savage-frontier#Ironmaster), see [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier).



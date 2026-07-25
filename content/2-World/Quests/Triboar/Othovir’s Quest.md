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
questGiver: "[[2-World/People/Triboar/Othovir.md|Othovir]]"
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
After his close call during the giants’ attack, [Othovir](https://www.dndbeyond.com/monsters/27616-othovir) expresses his gratitude to the characters by sharing a secret with them: he knows the location of a stash of magic items that the Margaster family, his kin, keeps locked away for emergencies. If the characters ask him how he came by this information, Othovir tells them that he has a history with the Margaster family, which he despises for reasons he’d rather not discuss. The family owns a three-story tower in Silverymoon that has a detached carriage house on the property, and it is here that the characters must travel. He provides the following details:

- The carriage house is a 30-foot-square stone building with two floors. The windowless ground floor that holds the carriage has a big wooden sliding door in the front. The upper floor is an apartment with a floor made of wooden planks and a barred window set into each wall. An open wooden staircase in one corner of the building connects the floors.
- Two human guards with spears are stationed in the upstairs apartment.
- An [arcane lock](https://www.dndbeyond.com/spells/2003-arcane-lock) spell protects the sliding wooden door.
- The carriage has two [draft horses](https://www.dndbeyond.com/monsters/16844-draft-horse) harnessed to it, ready to leave at a moment’s notice. The carriage is protected by an [alarm](https://www.dndbeyond.com/spells/1991-alarm) spell, set to go off when a carriage door is opened.
- The magic items are hidden in a compartment under the passenger seat inside the carriage.

Othovir doesn’t know what magic items are included in the stash. He also doesn’t know that the human guards are actually two [cambions](https://www.dndbeyond.com/monsters/17137-cambion) using [alter self](https://www.dndbeyond.com/spells/1992-alter-self) spells to conceal their true forms. The cambions are loyal to House Margaster and attack anyone they catch infiltrating the carriage house.

The [alarm](https://www.dndbeyond.com/spells/1991-alarm) spell not only attracts the cambions but also alerts Xamlyn Margaster (LE female Illuskan human [mage](https://www.dndbeyond.com/monsters/16947-mage)), who lives in the nearby tower. She emerges from the tower on the third round and casts spells at anyone trying to make off with the magic items or the carriage.

_**Treasure.**_ The compartment has four magic items. Determine two of them by rolling on [Magic Item Table C](https://www.dndbeyond.com/sources/dmg/treasure#MagicItemTableC) in [chapter 7](https://www.dndbeyond.com/sources/dmg/treasure) of the [Dungeon Master’s Guide](https://www.dndbeyond.com/sources/dmg), and the other two by rolling on [Magic Item Table B](https://www.dndbeyond.com/sources/dmg/treasure#MagicItemTableB).
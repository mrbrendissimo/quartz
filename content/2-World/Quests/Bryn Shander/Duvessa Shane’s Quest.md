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
questGiver: "[[Duvessa Shane|Duvessa Shane]]"
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

- [ ] [[Duvessa Shane]] is Alive
- [ ] Embark to [[Waterdeep]]
- [ ] Confront Osk Thunderhale at the Hanging Lantern
- [ ] Ride out and locate the wreckage of the Moon Maiden

# Quest Details


Date Obtained: `INPUT[datePicker:questObtained]` 
Status: `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` 
Quest Giver: `INPUT[suggester(optionQuery(#Category/People)):questGiver]` 
Quest Location: `INPUT[suggester(optionQuery(#Category/Hub)):questLocationObtained]` 
Session Obtained: `INPUT[suggester(optionQuery(#Category/Journal)):questSessionObtained]` 
Available Loot: `INPUT[suggester(optionQuery(#item)):questLootAvail]` 
Acquired Loot: `INPUT[suggester(optionQuery(#item)):questLookEarned]` 

# GM Notes

If the characters seek out information about the _Dancing Wave_, they learn that the ship is missing and several weeks overdue. It was transporting goods from [[Luskan]] to [[Waterdeep]] when it disappeared. Rumor has it that Neverwinter privateers aboard a ship called the _Moon Maiden_ sighted floating debris while traveling south to [[Waterdeep]].

The characters can find Osk Thunderhale (CN male Illuskan human [bandit captain](https://www.dndbeyond.com/monsters/16799-bandit-captain)), the captain of the _Moon Maiden_, taking it easy at the Hanging Lantern, a festhall near [[Waterdeep]]’s docks. Thunderhale is a skilled fiddler ([Performance](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills) +6). In fact, he’s playing his fiddle to amuse his crew and other festhall patrons when the characters show up to question him.

If they confront him, Thunderhale takes umbrage and tries to pick a fight. Twelve members of the _Moon Maiden_ crew (CN male Illuskan human [bandits](https://www.dndbeyond.com/monsters/16798-bandit)) stand ready to leap into the fray. If the characters reduce Thunderhale to 32 hit points or fewer, he surrenders, smiles, and offers his hand in friendship while complimenting the characters on their fighting prowess. If the characters defuse the situation by not responding to his initial attack, Thunderhale is just as pleased. He pays for their drinks and covers any damage to the festhall, then claims to be in the employ of Lord Dagult Neverember of Neverwinter.

Thunderhale has no proof that the debris he saw came from the _Dancing Wave_, but he’s aware of no other Waterdhavian merchant ships that have gone missing of late. Furthermore, he claims to have seen “a ship as big as a mountain” prowling the northern waters and thinks it might have attacked and destroyed the _Dancing Wave_. If the characters express interest in mounting a search, either for the _Dancing Wave_ or the mysterious vessel, Captain Thunderhale commits his ship and crew for 10 gp per day and two-thirds of whatever spoils are found. He can be talked down to an even split of the spoils with a successful DC 15 Charisma ([Persuasion](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check. Once a deal is reached, Thunderhale agrees to set sail whenever the characters are ready to depart, and he reminds them that they must secure their own provisions.

The _Moon Maiden_ is anchored in the bay and can be reached by rowboat. Eight crew members (CN male and female Illuskan human [bandits](https://www.dndbeyond.com/monsters/16798-bandit)) stand watch on deck while the ship is in port.

# Backstory

After dispatching scouts to check on the other settlements of Ten-Towns, Duvessa tells the characters that she has an aunt (her father’s sister) living in [[Waterdeep]] who is the captain of a ship called the _Dancing Wave_. Duvessa writes a letter to her aunt, Inirva Coldwater, asking her to provide passage and accommodations to the characters if they need to travel up or down the Sword Coast.

# Planning

_**Treasure.**_ Captain Thunderhale keeps a wooden treasure chest in his ship’s hold. It’s locked and rigged with a [[poisoned-needle-xdmg|Poisoned Needle]]. Thunderhale wears the key to the chest on a string around his neck. The chest contains 1,100 cp, 800 sp, 120 gp, nine 50 gp gemstones, and **1d4** magic items. Determine one magic item by rolling on [[magic-item-table-b|Magic Item Table B]], and any other magic items by rolling on [[magic-item-table-a|Magic Item Table A]].

# People

`BUTTON[button_person]` The following people are associated with this quest.

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender", Connected_Groups AS "Associated Group"
FROM "2-World/People"
WHERE contains(char_status, "Alive")
WHERE contains(Connected_Quests, this.file.link)
SORT file.name ASC
```





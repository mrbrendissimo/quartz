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
questGiver:
questLocationObtained:
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

###  Sirac of Suzail’s Quest

Realizing that the frost giants are after the _Ring of Winter_, Sirac confesses to the characters after the battle that he’s the son of Artus Cimber, and says that he believes his father has the ring. Although he doesn’t know his father’s present whereabouts, Sirac recalls that Artus had connections to the Roaringhorns, a noble family in Waterdeep. He urges the characters to visit the Roaringhorn estate in Waterdeep and speak to someone there. Fearing that the frost giants might come after him again, Sirac offers to accompany the characters as far south as [[Luskan]], where he can catch a ship heading south. Guided by Jarl Storvald’s [blod stone](https://www.dndbeyond.com/magic-items/5511-blod-stone), the frost giants continue hunting for Sirac. If the characters allow Sirac to accompany them, assume that any frost giants that appear in a random encounter are searching for him.

If they travel to Waterdeep, the characters learn that the Roaringhorn family has a villa, called the High House of Roaringhorn, in the city’s North Ward. Although it’s one of the grandest residences in Waterdeep, and currently hosting one of its many infamous parties, this one a welcome celebration for visiting relatives from Cormyr. Upon their arrival, the adventurers are greeted by Lord Zelraun Roaringhorn (LN male Chondathan human [archmage](https://www.dndbeyond.com/monsters/16789-archmage)). Having quaffed a few [potions of longevity](https://www.dndbeyond.com/magic-items/5359-potion-of-longevity) in his lifetime, he has the appearance and vigor of a thirty-year-old despite his being a couple decades older than that. A [shield guardian](https://www.dndbeyond.com/monsters/17012-shield-guardian) accompanies Zelraun at all times. Zelraun tells the characters (truthfully) that he has no idea where Artus is, and all prior attempts to divine his whereabouts or scry on him with magic have failed. Zelraun hides the fact that both he and Artus are Harpers, although he secretly suspects Artus has “gone rogue.” Even if Zelraun knew where Artus was, it would be improper for him to divulge such information and potentially expose another member of the Harpers to harm.

Zelraun asks the characters who sent them in his direction. If they reply truthfully, he engages them in conversation about where they have come from and where they’re headed next.

_**Treasure.**_ Once he realizes that the characters have important work ahead of them, Zelraun gives each of them a magic item. To determine each item, roll on [Magic Item Table B](https://www.dndbeyond.com/sources/dmg/treasure#MagicItemTableB) in [chapter 7](https://www.dndbeyond.com/sources/dmg/treasure) of the [Dungeon Master’s Guide](https://www.dndbeyond.com/sources/dmg), or allow each player to choose one item from that table.
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




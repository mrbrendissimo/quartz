---
tags:
  - Category/Quest
MyContainer: "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
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

Every bone in her body tells [Naxene](https://www.dndbeyond.com/monsters/27594-naxene-drathkala) that the attack on Goldenfields is just the beginning. She’s heard “rumblings” that other settlements have been impacted by the sudden appearance of giants — and not just hill giants but also stone, frost, fire, and cloud giants. Naxene is convinced that now is not the time for half-measures. She has read books about the ancient conflict between dragons and giants, and she urges the characters to seek out a powerful good dragon, convince it to contact other good dragons, and use them to combat the giants. Naxene is confident that the Lords’ Alliance will support this plan, given the gravity of the situation. She couldn’t be more wrong.

Naxene is unaware that the Lords’ Alliance leaders would rather hurl themselves into the Nine Hells than deal with dragons. She recommends that the party speak to an acquaintance of hers — a “dragon expert” in Waterdeep named Chazlauth Yarghorn (CN male Illuskan human [mage](https://www.dndbeyond.com/monsters/16947-mage)). Naxene provides directions to his residence in the city’s North Ward: a tall stone house with a tower on one corner.

Chazlauth has a [silver dragon wyrmling](https://www.dndbeyond.com/monsters/17014-silver-dragon-wyrmling) companion named Irizzorl that he keeps hidden in his tower, along with several [cats](https://www.dndbeyond.com/monsters/16820-cat) that the dragon likes to terrorize. The racket in the tower is constant during the party’s visit, during which Chazlauth dismisses Naxene’s crazy plan and proposes an even crazier one. He suggests that the characters travel to the Kryptgarden Forest and seek out Old Gnawbone, a powerful and eccentric green dragon rumored to possess a collection of [crystal balls](https://www.dndbeyond.com/magic-items/4610-crystal-ball) that she uses to scry on everyone and everything. Based on what Chazlauth knows about green dragons, and Old Gnawbone in particular, he doesn’t think the dragon will harm the characters if they seem intent on ending the giant threat, and he’s willing to risk their lives to test his theory.

_**Treasure.**_ If the characters agree to seek out Old Gnawbone, Chazlauth plucks a handful of potions from a shelf in his tower and gives one to each character. One of them is a [potion of poison](https://www.dndbeyond.com/magic-items/4712-potion-of-poison) that has been mislabeled “[Potion of Poison Resistance](https://www.dndbeyond.com/magic-items/5141-potion-of-poison-resistance).” The others are actual [potions of poison resistance](https://www.dndbeyond.com/magic-items/5141-potion-of-poison-resistance). All the potions look the same; roll randomly to determine which character receives the poison one.

_**Development.**_ Run the suggested encounter in the “[Kryptgarden Forest](https://www.dndbeyond.com/sources/skt/the-savage-frontier#KryptgardenForest)” section in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier) once the characters enter Old Gnawbone’s domain.

# People

`BUTTON[button_person]` The following people are associated with this quest.

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender", Connected_Groups AS "Associated Group"
FROM "2-World/People"
WHERE contains(char_status, "Alive")
WHERE contains(Connected_Quests, this.file.link)
SORT file.name ASC
```





---
tags:
  - Category/Quest
MyContainer:
  - "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
  - "[[2-World/Hubs/Goldenfields.md|Goldenfields]]"
MyCategory:
obsidianUIMode: preview
questObtained:
questStatus: Not Started
questGiver: "[[2-World/People/Goldenfields/Oren Yogilvy.md|Oren Yogilvy]]"
questLocationObtained: "[[2-World/Hubs/Goldenfields.md|Goldenfields]]"
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

[Oren](https://www.dndbeyond.com/monsters/27595-oren-yogilvy) is spooked by rumors that giants are rampaging throughout the North. He asks the characters if they could check on his sister, Lily, who works at the Happy Cow tavern in Daggerford. He also wants them to deliver a hastily written letter to Lily that tells her he’s doing fine, and would she please send him some more money.

Lily (LG female strongheart halfling [commoner](https://www.dndbeyond.com/monsters/16829-commoner)) married into the Hardcheese family, which owns and operates the Happy Cow tavern in Daggerford. The real family business, however, is moneylending. The halflings use the tavern to attract new clients, and while the Happy Cow breaks even, it’s not a big moneymaker, and right now the Hardcheese moneylending business is on the ropes. The Black Network has agents in Daggerford handing out interest-free loans (but breaking the arms of anyone who fails to pay up); the Hardcheeses simply can’t compete.

If the characters deliver Oren’s letter to Lily, her husband Koggin Hardcheese (LG male strongheart halfling [commoner](https://www.dndbeyond.com/monsters/16829-commoner)) asks them to speak with Nelkin “the Snail” Danniker, a Zhentarim operative who is staying at the River Shining Tavern and Inn, and kindly tell him to back off. Koggin would do it himself, but he thinks that the adventurers stand a better chance of persuading the Snail to relent. Nelkin is described in the “[Daggerford](https://www.dndbeyond.com/sources/skt/the-savage-frontier#Daggerford)” section in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier). If the characters agree to his terms, as outlined in that section, Nelkin will stop undermining the Hardcheeses’ moneylending business.

_**Treasure.**_ Oren gives the party a cask of Goldengulp (worth 15 gp) as a gift before they leave Goldenfields.

Koggin Hardcheese gives the characters a cornucopia stuffed with fresh fruit and bread if they come to terms with the Snail. If the characters are visibly unhappy with this reward, he throws in a bottle of winterberry wine (worth 10 gp).

# People

`BUTTON[button_person]` The following people are associated with this quest.

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender", Connected_Groups AS "Associated Group"
FROM "2-World/People"
WHERE contains(char_status, "Alive")
WHERE contains(Connected_Quests, this.file.link)
SORT file.name ASC
```





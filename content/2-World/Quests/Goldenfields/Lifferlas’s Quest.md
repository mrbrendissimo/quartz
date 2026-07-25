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
questGiver: "[[2-World/People/Goldenfields/Lifferlas.md|Lifferlas]]"
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

# People

`BUTTON[button_person]` The following people are associated with this quest.

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender", Connected_Groups AS "Associated Group"
FROM "2-World/People"
WHERE contains(char_status, "Alive")
WHERE contains(Connected_Quests, this.file.link)
SORT file.name ASC
```



# GM Notes

#### Lifferlas’s Quest

[[Lifferlas]] urges the characters to seek out its creator, a moon elf druid named Aerglas. The [[awakened-tree-xmm|awakened tree]] tells them that Aerglas was not only a member of the [[Emerald Enclave|Emerald Enclave]] but also an adventurer who slew many giants in his day. Aerglas left [[Goldenfields]] thirty years ago on a pilgrimage to [Shadowtop Cathedral](https://www.dndbeyond.com/sources/skt/the-savage-frontier#ShadowtopCathedral) (see [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier)). The druid planned to follow the Dessarin River and seek out an old [[treant-xmm|treant]] named [[turlang-skt|Turlang]]. [[Lifferlas]] suggests that the characters do the same.

[[turlang-skt|Turlang]] isn’t at Shadowtop Cathedral when the characters arrive, but a morose [[satyr-xmm|satyr]] named Greenwhistle assures them that the [[treant-xmm|Treant]] “will be along any time now.” Greenwhistle is disappointed because a dryad spurned his advances, so he sits by a pool playing sad songs on his panpipes day and night. Between songs, Greenwhistle repeatedly assures the characters that Turlang “will be along any time now.” The treant arrives on the third night after the characters arrive, in the company of a friend named Tharra Shyndle (NG female half-elf [druid](https://www.dndbeyond.com/monsters/16848-druid)), who is a member of the [[Emerald Enclave|Emerald Enclave]]

The treant is initially indifferent toward the heroes and not of a mind to please. If one or more characters approach the treant in a nonthreatening manner and initiates a conversation, Tharra urges the treant not to lose its temper. The treant groans audibly and answers brusquely. It doesn’t know Lifferlas but remembers Aerglas fondly. The treant hasn’t seen the druid in many years and doesn’t know where Aerglas can be found. If the characters reveal their opposition to the giants, Turlang offers them help in the form of two [awakened trees](https://www.dndbeyond.com/monsters/16792-awakened-tree) and one [awakened shrub](https://www.dndbeyond.com/monsters/16791-awakened-shrub). These awakened plants speak Common and heed the party’s commands.

_**Treasure.**_ Tharra offers to guide the party to the [[Evermoor Way]], north of the forest. If they accept, they have no hostile encounters en route. Once they reach the forest’s edge, Tharra makes a decision whether to befriend the characters or not. If they seem friendly and show concern for the fate of the natural world, she declares her friendship by giving them a pouch of 1d4 + 4 magical silver berries that she picked near the Lost Peaks. Swallowing a berry has the same effect as imbibing a [potion of invisibility](https://www.dndbeyond.com/magic-items/4710-potion-of-invisibility). If one or more characters are destructive and rude, she bids them farewell upon reaching the forest’s edge and heads off on her own.

_**Development.**_ As she guides the characters through the forest, Tharra says she plans to visit an old friend — a ranger named Quinn Nardrosz who lives in [[Jalanthar]]. If she’s friendly toward the characters, she invites them to join her, saying she could use the company. If the characters accept the invitation, Tharra leads them to [[Everlund]], then east to [[Jalanthar]] by way of the Rauvin Road. Quinn is so delighted that the characters took the trouble to accompany Tharra that he gives them three magic items that he “acquired” during his days as an adventurer; roll on [Magic Item Table F](https://www.dndbeyond.com/sources/dmg/treasure#MagicItemTableF) in [chapter 7](https://www.dndbeyond.com/sources/dmg/treasure) of the [Dungeon Master’s Guide](https://www.dndbeyond.com/sources/dmg) for the first item, and on [Magic Item Table B](https://www.dndbeyond.com/sources/dmg/treasure#MagicItemTableB) for the other two.
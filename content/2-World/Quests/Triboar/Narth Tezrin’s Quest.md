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
questGiver: "[[2-World/People/Triboar/Narth Tezrin.md|Narth Tezrin]]"
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

A few months ago, the [[Lionshield Coster]] received a payment from one Amrath Mulnobar, castellan of [[Noanar’s Hold]], for five horse harnesses made by none other than Triboar’s finest harness-maker, Othovir. Othovir recently finished the last of the harnesses, and Narth needs to arrange for their delivery to Noanar’s Hold. Since the recent giant attack, he has become worried about the safe arrival of the shipment. Narth has never been to Noanar’s Hold, but he describes it as a village near the High Forest that once attracted wealthy hunters.

[Narth](https://www.dndbeyond.com/monsters/27610-narth-tezrin) packs the harnesses in a large crate with the Lionshield Coster emblem painted on its sides and asks the characters to make the delivery for him. If they accept the quest, he tells them how to get to Noanar’s Hold by following the [[Evermoor Way]]. When they’re ready to leave, assuming they haven’t made provisions to transport the shipment by other means, Narth has a cart waiting for them with the crate loaded on it, pulled by a draft horse named Boris.

_**Treasure.**_ Narth offers them 100 gp up front to make the delivery. Narth also lets the characters keep Boris and the cart once they complete the delivery.

_**Development.**_ When the characters arrive at Noanar’s Hold, they are told that they can find Amrath Mulnobar in the keep overlooking the village. Amrath takes the harnesses off their hands without so much as a thank-you. Thus ends the quest.

With no other settlements nearby, the characters might be inclined to spend the night in the White Hart Inn, where they meet three middle-aged brothers from Neverwinter (LE male Illuskan human [nobles](https://www.dndbeyond.com/monsters/16966-noble)) who are gearing up for a hunt. Their names are Rantharl, Marthun, and Lezryk Daerivoss, and they tell the characters that they’ve come to Noanar’s Hold to hunt hill giants. The brothers don’t want company. They quietly saddle their horses, strap on their rapiers, and ride out at dawn. The younger brothers return before dusk, but Rantharl is not with them, and Marthun has a laceration on his right shoulder that a successful DC 11 Wisdom ([Medicine](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check confirms is a rapier wound.

If pressed, the brothers claim that a hill giant killed Rantharl. Marthun claims that he was struck by the giant’s spiked greatclub and denies any assertion that his wound was caused by a rapier. A successful DC 15 Wisdom ([Insight](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check confirms that Marthun and Lezryk are lying, though Marthun welcomes any healing that the characters can provide.

The brothers are playing a murderous game with their inheritances at stake. The agreement was simple: the brother who first deals the killing blow to a hill giant would gain the inheritances of the other two. Rantharl won the contest, but Marthun and Lezryk turned against him. A fight ensued, Marthun was wounded, and Rantharl died. With Rantharl gone and no clear winner, Marthun and Lezryk have agreed to track down another hill giant.

If the characters follow the brothers on their hunt and are spotted, the brothers attack them. If the characters do nothing, Marthun and Lezryk begin another hunt the following day, but they encounter no hill giants. Lezryk betrays and kills Marthun, then returns to the inn to rest before making the long trip back to Neverwinter to deliver the sad news of his brothers’ untimely deaths at the hands of “rampaging hill giants.” Characters can blackmail Lezryk for a cut of the brothers’ inheritance (worth 10,000 gp total), or deal with the treacherous cad in some other manner as they see fit.
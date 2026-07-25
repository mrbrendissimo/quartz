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
questGiver: "[[2-World/People/Triboar/Urgala Meltimer.md|Urgala Meltimer]]"
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

In the aftermath of the battle, [Urgala](https://www.dndbeyond.com/monsters/27612-urgala-meltimer) relates to the characters that one of her former adventuring companions, a wealthy knight named Harthos Zymorven, had a [giant slayer greatsword](https://www.dndbeyond.com/magic-items/4904-giant-slayer-greatsword). (Change the weapon to a [giant slayer greataxe](https://www.dndbeyond.com/magic-items/4903-giant-slayer-greataxe) if that would be more desirable to a party member.) The last time Urgala spoke with him, Harthos was living in[[Zymorven Hall]], his ancestral keep on the Rauvin Road northwest of Silverymoon. Urgala thinks Harthos might be willing to part with the weapon if the characters mention her name to him and explain their reason for needing it.

If the characters journey to Zymorven Hall, they find Lord Harthos Zymorven, but he is sad to report that his son Harthal has stolen the [giant slayer](https://www.dndbeyond.com/magic-items/5388-giant-slayer). Harthal committed this act after Lord Zymorven disowned him for marrying a common thief from Yartar (whose name he doesn’t recall). What Harthal did with the sword, Lord Zymorven can only imagine.

The characters can travel to [[Yartar]] and search for Harthal there. After a few polite inquiries, it becomes apparent that the local thieves’ guild, the Hand of Yartar, might be their best hope of finding Harthal. A character can bribe a tavern server at the Wink and Kiss (5 gp is sufficient) to learn the identity and whereabouts of a known Hand of Yartar member. They’re as common as rats. If the characters obtained a letter of recommendation from Tamalin Zoar (see the “[Calling Horns](https://www.dndbeyond.com/sources/skt/the-savage-frontier#CallingHorns)” section in [chapter 3](https://www.dndbeyond.com/sources/skt/the-savage-frontier)), they can show it to the Hand of Yartar member, who promises to have the information they need in a few hours. Otherwise, the thief demands a 500 gp payment up front. When the thief returns 1d6 hours later, she tells the characters that Harthal was arrested and imprisoned for murdering a man, and the greatsword found its way into the hands of a corrupt watch captain named Tholzar Brenner (LE male Damaran human [knight](https://www.dndbeyond.com/monsters/16938-knight)).

The characters can try to relieve Brenner of the weapon by force. The man has many enemies, so he usually travels with eight [guards](https://www.dndbeyond.com/monsters/16915-guard) (LE male and female humans of various ethnicities). He refuses to relinquish the weapon willingly. Under normal circumstances, the death or disappearance of a watch member would trigger an investigation, but in Captain Brenner’s case, Waterbaron Nestra Ruthiol is happy to be rid of him and doesn’t order one.

Any character who belongs to the Harpers or the Zhentarim can approach his or her faction for help. If the character succeeds on a DC 15 Intelligence ([Investigation](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check, he or she locates a faction safe house and gains entry. A failed check can be rerolled after another day spent searching, until a check succeeds or the character gives up the search. Inside the safe house, the character meets a faction representative, who sets a few wheels in motion. A few hours later, the stolen weapon is delivered to the safe house.

A character who belongs to the Lords’ Alliance can petition the Waterbaron for help. The character must succeed on a DC 15 Charisma ([Deception](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills) or [Persuasion](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check to gain an audience. [Deception](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills) is appropriate if the character makes false claims to gain an audience; otherwise, use [Persuasion](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills). A failed check can be rerolled the next day, but each failed check increases the DC by 1. If a character succeeds on this check, the Waterbaron wrests the sword from Captain Brenner’s clutches and sees it delivered safely to that individual.

_**Treasure.**_ Lord Zymorven’s weapon is indeed a [giant slayer greatsword](https://www.dndbeyond.com/magic-items/4904-giant-slayer-greatsword) (or [greataxe](https://www.dndbeyond.com/magic-items/4903-giant-slayer-greataxe)).
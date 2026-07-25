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
questGiver:
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
>> 
>[![](https://www.dndbeyond.com/attachments/thumbnails/1/954/850/563/skt02-06.png)](https://www.dndbeyond.com/attachments/1/954/skt02-06.png)
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



#### Beginning the Encounter

>[!REARD ALOUD]+ READ ALOUD 
>Around highsun, the town is shaken from its peacefulness by the screams of women and children, followed by a man yelling, “Giants! Run!” Perplexed residents and shopkeepers emerge from their domiciles in time to see a large rock fall from the sky and crash onto an old cart, splintering it. As a cloud of dust erupts from the wreckage, a second rock hits the ground, tumbles through a fence, and slams against the wall of a building, startling a pair of mules tethered to a post nearby. All around you, people begin to shriek and scatter.

Okssort and Ildmane’s plan is to barge into town, dig up the Vonindod fragment, and haul it back to Ironslag (see chapter 8, “[Forge of the Fire Giants](https://www.dndbeyond.com/sources/skt/forge-of-the-fire-giants)”), destroying anything that gets in their way. As they approach the center of Triboar, they hurl boulders into the town to strike fear into the hearts of the townsfolk, hoping to frighten most of them away. The magmins run alongside the giants, eager to please. Whenever a fire giant points to a building or other flammable structure, a gang of magmins runs toward the target and tries to set it ablaze.

The orogs, clad in heavy plate mail, march ahead of the fire giants, knocking down fences and clearing the way of rabble. Anything the orogs don’t knock down is crushed underfoot by the advancing fire giants. The orogs spread through town, attacking civilians who cross their path and drawing attention away from the fire giants.

The orcs ride their axe beaks into town after the initial volley of boulders. Their job is to distract the town’s defenders and engage enemy archers in melee combat. The axe beaks act on the orcs’ initiative count. Rules for [mounted combat](https://www.dndbeyond.com/sources/phb/combat#MountedCombat) can be found in [chapter 9](https://www.dndbeyond.com/sources/phb/combat) of the [Player’s Handbook](https://www.dndbeyond.com/sources/phb).

The fire giants and their entourage approach from the northeast, damaging [[T11. Othovir’s Harness Shop]] and destroying Ransor’s Open Road ( [[T7. Ransor’s Open Road|T7]] as they make their way toward the north campground ([[T2. North Caravan Campground|T2]]. The fire giants are so intimidating that most townsfolk stop what they’re doing and flee, heading south along the [[Long Road]]. Others hunker down in their homes and businesses.

If either fire giant is reduced to 81 hit points or fewer, the giants realize that they have underestimated Triboar’s defenses. They quickly leave the way they came while commanding their underlings to cover their retreat.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#DefenseofTriboar)Defense of Triboar

After receiving reports of orcs attacking ranches to the southeast, Lord Protector Darathra Shendrel sends the Twelve to Merrymeadow Ranch and Broken Yoke Ranch to ascertain the extent of the danger and aid the ranchers. These attacks are merely distractions. While the Twelve are away, the fire giants attack from the northeast, leaving the adventurers and a handful of determined townsfolk to defend the town. 

>[!Note]+ Give each player one of the following NPCs to play during this encounter:
>[[[Darathra Shendrel]], Lord Protector of Triboar (starts at [area [[T1. Market Square and Tower|T1]]
>[[Darz Helgar]], campground caretaker (starts at [area [[T2. North Caravan Campground|T2]]
>[[Narth Tezrin]],  [[Lionshield Coster]] representative (starts at [area [[T6. The Lion’s Share|T6]]
>[[Urgala Meltimer]] starts at [[T10. Northshield House]]
>[[Othovir]], harness-maker (starts at  [[T11. Othovir’s Harness Shop]]
>[[Ghelryn Foehammer]] area [[T18. Foehammer’s Forge|T18]]

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#VonindodFragment)Vonindod Fragment

Ildmane clutches a [rod of the Vonindod](https://www.dndbeyond.com/magic-items/5524-rod-of-the-vonindod), which guides her to [[T2. North Caravan Campground|North Caravan Campground]]. When the fire giants arrive there, they use their greatswords like shovels, digging up the ground to reach the Vonindod fragment — a bent and broken band of 2-inch-thick adamantine roughly 11 feet long and weighing 1,000 pounds. It takes ten actions by the giants to unearth the C-shaped fragment, and another action for one of them to pull it free. One fire giant can carry the fragment using both hands or drag it using one hand.

Any character who inspects the broken adamantine ring can, with a successful DC 15 Intelligence ([Arcana](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) check, determine that it was once part of some kind of enormous construct. Casting a [detect magic](https://www.dndbeyond.com/spells/2065-detect-magic) spell on the fragment reveals a faint, lingering magical aura, though the school of magic can’t be ascertained. If the characters obtain the fragment, Alaestra Ulgar (see [[T6. The Lion’s Share]]] and Urlam Stockspool (see [[T9. The Triboar Travelers]] each offers to buy it for 5,000 gp (paid in 500 gp gemstones), though its actual value is three times as much.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#AttackonTriboarTreasure)Treasure

Ildmane carries no treasure other than a [rod of the Vonindod](https://www.dndbeyond.com/magic-items/5524-rod-of-the-vonindod) (see [appendix B](https://www.dndbeyond.com/sources/skt/magic-items#RodoftheVonindod)). Okssort carries a sack holding 1d6 mundane items, determined by rolling on the [Items in a Giant’s Bag](https://www.dndbeyond.com/sources/skt/introduction#ItemsinaGiantsBag) table in the [introduction](https://www.dndbeyond.com/sources/skt/introduction), and a ruby pendant (worth 750 gp). The magmins and the orcs have no treasure. Each orog carries a pouch that holds 1d20 gp in mixed coinage.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#AttackonTriboarDevelopment)Development

If the fire giants obtain the Vonindod fragment and leave town, they make the long trek back to Ironslag with their prize, avoiding roads and settlements. If the fire giants are forced to leave without the Vonindod fragment, they retreat to the [[Surbrin Hills]] and roust four hill giants, returning to Triboar 2d4 + 2 days after their initial attack. This time, they fight to the death to claim the fragment for their lord and master, Duke Zalto. The adventurers need not feel obliged to stay and defend the town from this second attack, because the local militia has been assembled and placed on alert.

Whether or not the characters thwart the fire giants, they gain special quests and rewards based on which NPCs survived the initial battle.
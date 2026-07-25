---
MyContainer: "[[2-World/People/Bryn Shander/Artus Cimber]]"
MyCategory:
tags:
  - Category/Item
obsidianUIMode: preview
aliases:
  - ItemOtherName
Connected_Quests:
  - "[[z_Templates/World Builder Templates/Template-Quest.md|Template-Quest]]"
Connected_Groups:
  - "[[z_Templates/World Builder Templates/Template-Group.md|Template-Group]]"
weight: 1
char_gender:
  - Magical
  - Artifact
---



> [!NOTE|div-m] Parent Location: `INPUT[inlineListSuggester(optionQuery(#Category/Quest),optionQuery(#Category/People),optionQuery(#Category/Group),optionQuery(#Category/Place),optionQuery(#Category/PointofInterest)):MyContainer]`

> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[items-Ring_of_Winter.webp|500]]
>
>> [!div-m|no-title] Place Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️Description),
>> option(2, ⚔️Features),
>> option(3, 🔗Connections),
>> option(4, 📝GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#Description|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#Features|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#Connections|no-h clean]]
>>> 
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 

# Description

This is the items description. 

---

*Source:*

# Features

Cost: `INPUT[number:cost]`

Weight: `INPUT[number:weight]`

Category: `INPUT[inlineListSuggester(option(Alchemical), option(Artifact), option(Consumable), option(Cursed), option(Intelligent), option(Invested), option(Magical), option(Relic), option(Rune), option(Snare), option(Stance), option(Talisman), option(Worn)):char_gender]`

---
|   |   |   |   |   |   |
|---|---|---|---|---|---|
||   |   |   |   |   |
|[Artus Cimber](https://5e.tools/bestiary.html#artus%20cimber_toa) has kept this item in his possession for over a century. The _Ring of Winter_ is a golden band that resizes to fit snugly on the finger of its wearer. A thin layer of frost coats the outside of the ring, which normal heat can't melt. The ring feels ice cold to the touch and initially numbs the hand that wears it, but this cold ceases to be felt by one who is attuned to this ring.<br><br>The _Ring of Winter_ is sentient and tries to take control of any creature that wears it (see "Sentient Magic Items" chapter 7 of the Dungeon Master's Guide). If it succeeds, the ring compels its wearer to cause undue harm to everyone and everything around it, in a cold-hearted attempt to incur the wrath of enemies and bring the wearer's doom.<br><br>Sentience. The _Ring of Winter_ is a sentient chaotic evil item with an Intelligence of 14, a Wisdom of 14, and a Charisma of 17. The ring communicates by transmitting emotion to the creature carrying or wielding it, and it has hearing and normal vision out to a range of 60 feet. The ring craves destruction, and it likes inflicting indiscriminate harm on others.<br><br>Nondetection. The _Ring of Winter_ defies attempts to magically locate it. Neither the ring nor its wearer can be targeted by any divination magic or perceived through magical scrying sensors.<br><br>Frozen Time. As long as you wear the ring, you don't age naturally. This effect is similar to suspended animation, in that your age doesn't catch up to you once the ring is removed. The ring doesn't protect its wearer from magical or supernatural aging effects, such as the Horrifying Visage of a [ghost](https://5e.tools/bestiary.html#ghost_mm).<br><br>Cold Immunity. While attuned to and wearing the ring, you have immunity to cold damage and don't suffer any ill effects from extreme cold (see chapter 5 of the Dungeon's Master Guide).<br><br>Magic. The _Ring of Winter_ has 12 charges and regains all its expended charges daily at dawn. While wearing the ring, you can expend the necessary number of charges to activate one of the following properties:<br><br>- You can expend 1 charge as an action and use the ring to lower the temperature in a 120-foot-radius sphere centered on a point you can see within 300 feet of you. The temperature in that area drops 20 degrees per minute, to a minimum of -30 degrees Fahrenheit. Frost and ice begin to form on surfaces once the temperature drops below 32 degrees. This effect is permanent unless you use the ring to end it as an action, at which point the temperature in the area returns to normal at a rate of 10 degrees per minute.<br>- You can cast one of the following spells from the ring (spell save DC 17) by expending the necessary number of charges: [Bigby's hand](https://5e.tools/spells.html#bigby's%20hand_phb) (2 charges; the hand is made of ice, is immune to cold damage, and deals bludgeoning damage instead of force damage as a clenched fist), [cone of cold](https://5e.tools/spells.html#cone%20of%20cold_phb) (2 charges), flesh to ice (3 charges; as [flesh to stone](https://5e.tools/spells.html#flesh%20to%20stone_phb) except that the target turns to solid ice with the density and durability of stone), [ice storm](https://5e.tools/spells.html#ice%20storm_phb) (2 charges), [Otiluke's freezing sphere](https://5e.tools/spells.html#otiluke's%20freezing%20sphere_phb) (3 charges), [sleet storm](https://5e.tools/spells.html#sleet%20storm_phb) (1 charge), [spike growth](https://5e.tools/spells.html#spike%20growth_phb) (1 charge; the spikes are made of ice), or [wall of ice](https://5e.tools/spells.html#wall%20of%20ice_phb) (2 charges).<br>- You can expend the necessary number of charges as an action and use the ring to create either an inanimate ice object (2 charges) or an animated ice creature (4 charges). The ice object can't have any moving parts, must be able to fit inside a 10-foot cube, and has the density and durability of metal or stone (your choice). The ice creature must be modeled after a beast with a challenge rating of 2 or less. The ice creature has the same statistics as the beast it models, with the following changes: the creature is a construct with vulnerability to fire damage, immunity to cold and poison damage, and immunity to the following conditions: [charmed](https://5e.tools/conditionsdiseases.html#charmed_phb), [exhaustion](https://5e.tools/conditionsdiseases.html#exhaustion_phb), [frightened](https://5e.tools/conditionsdiseases.html#frightened_phb), [paralyzed](https://5e.tools/conditionsdiseases.html#paralyzed_phb), [petrified](https://5e.tools/conditionsdiseases.html#petrified_phb), and [poisoned](https://5e.tools/conditionsdiseases.html#poisoned_phb). The ice creature obeys only its creator's commands. The ice object or creature appears in an unoccupied space within 60 feet of you. It melts into a pool of normal water after 24 hours or when it drops to 0 hit points. In extreme heat, it loses 5 (1d10) hit points per minute as it melts. Use the guidelines in chapter 8 of the Dungeon Master's Guide to determine the hit points of an inanimate object if they become necessary.<br><br>Other Properties. The _Ring of Winter_ is rumored to possess other properties that can be activated only by an evil being whose will the ring can't break. Frost giants have long believed that the ring can be used to freeze entire worlds, while a [djinni](https://5e.tools/bestiary.html#djinni_mm) in the service of a Calishite pasha once claimed that the ring could be used to summon and control white dragons, as well as the mighty ice primordial named Cryonax.<br><br>Destroying the Ring. The ring is nigh indestructible, resisting even the most intense magical heat. If it is placed on the finger of the powerful archfey known as the Summer Queen, the ring melts away and is destroyed forever.|   |   |   |   |   |
|**Source:** _ToA_, page 207|   |   |   |   |   |
# GM Notes

Make notes of what you need to track in the town here.  Secrets perhaps?

# Connections
Is the item linked to any groups or quests?

Quests: `INPUT[inlineListSuggester(optionQuery(#Category/Quest)):Connected_Quests]`

Groups: `INPUT[inlineListSuggester(optionQuery(#Category/Group)):Connected_Groups]`

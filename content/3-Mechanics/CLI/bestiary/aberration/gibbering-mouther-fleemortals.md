---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gibbering Mouther
---
# [Gibbering Mouther](3-Mechanics\CLI\bestiary\aberration/gibbering-mouther-fleemortals.md)
*Source: Flee, Mortals! p. 114*  

```statblock
"name": "Gibbering Mouther (FleeMortals)"
"size": "Medium"
"type": "aberration"
"subtype": "Controller"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "12"
  - !!int "16"
  - !!int "7"
  - !!int "10"
  - !!int "5"
"speed": "10 ft., fly 10 ft. (hover), swim 10 ft."
"saves":
  - "constitution": !!int "5"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "speaks all languages but doesn't understand any"
"cr": "2"
"traits":
  - "desc": "The gibbering mouther is immune to any power, spell, or effect that would\
      \ alter their form."
    "name": "Immutable Form"
  - "desc": "A [dazed](/3-Mechanics/CLI/conditions.md#Dazed) enemy who starts their\
      \ turn within 20 feet of the gibbering mouther must make a DC 13 Wisdom saving\
      \ throw. On a failed save, that creature's body is altered in an otherworldly\
      \ way of the GM's choice—they might flicker in and out of reality, sprout miniature\
      \ fingers from their fingers, or have their physical form altered in a similarly\
      \ alien way. This alteration doesn't affect the creature's game statistics.\
      \ A cure ailment power of 4th order or higher, a [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell, or a similar supernatural effect reverses this alteration.\n\nWhile\
      \ altered in this way, a creature must repeat the saving throw whenever they\
      \ finish a long rest. On a failed save, their previous alteration worsens or\
      \ they experience another chaotic alteration of the GM's choice. If a creature\
      \ fails this saving throw three times after their initial alteration, they transform\
      \ into a gibbering mouther controlled by the GM, and only a [wish](/3-Mechanics/CLI/spells/wish-xphb.md)\
      \ spell can restore the creature to their original form."
    "name": "Primordial Influence"
  - "desc": "The gibbering mouther envelops their surroundings in their shifting reality.\
      \ The area within 20 feet of them is difficult terrain for other creatures."
    "name": "Viscous Vicinity"
"actions":
  - "desc": "The gibbering mouther makes two Reality Rend attacks. They can replace\
      \ one attack with a use of Pull."
    "name": "Multiattack"
  - "desc": "Melee Power Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
      \ + 3) psychic damage, and the target must succeed on a DC 13 Wisdom saving\
      \ throw or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed) until the start\
      \ of the gibbering mouther's next turn."
    "name": "Reality Rend"
  - "desc": "The gibbering mouther warps reality around up to three creatures they\
      \ can see within 60 feet of them. Each target must succeed on a DC 13 Strength\
      \ saving throw or be pulled up to 30 feet directly toward the gibbering mouther."
    "name": "Pull"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/gibbering-mouther-fleemortals.png"
```
^statblock
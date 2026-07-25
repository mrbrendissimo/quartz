---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Shambling Mound Companion
---
# [Shambling Mound Companion](3-Mechanics\CLI\bestiary\plant/shambling-mound-companion-fleemortals.md)
*Source: Flee, Mortals! p. 225*  

```statblock
"name": "Shambling Mound Companion (FleeMortals)"
"size": "Large"
"type": "plant"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "14"
  - !!int "5"
  - !!int "10"
  - !!int "5"
"speed": "30 ft."
"saves":
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+0 plus PB"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 0"
"languages": ""
"traits":
  - "desc": "While the mound remains motionless, they are indistinguishable from an\
      \ ordinary mass of vegetation. If the mound's caregiver is Large or smaller,\
      \ they can use the Hide action to attempt to hide in the same space as their\
      \ motionless mound."
    "name": "False Appearance"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Vine Lash)"
  - "desc": "The mound makes a signature attack with a reach of 30 feet instead of\
      \ 5 feet.\n\nIf this attack hits a Medium or smaller creature, the mound can\
      \ pull the target up to 10 feet toward the mound."
    "name": "1st Level: Long-Range Lash (2 Ferocity)"
  - "desc": "The mound targets up to PB creatures within 30 feet of them who are Large\
      \ or smaller. Each target must succeed on a DC 10 plus PB Dexterity saving throw\
      \ or be pulled up to 15 feet toward the mound and take PBd4 poison damage."
    "name": "3rd Level: Verdant Roundup (5 Ferocity)"
  - "desc": "The mound attempts to pull a Large or smaller creature within 5 feet\
      \ of them into their body. The target must make a DC 10 plus PB Strength saving\
      \ throw. On a failure, the target is pulled into the mound's space, takes PBd8\
      \ poison damage, and is engulfed. On a success, a creature takes half as much\
      \ damage, doesn't move, and isn't engulfed.\n\nAn engulfed creature is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ has total cover against attacks and other effects outside the mound, and takes\
      \ PBd8 poison damage at the start of each of the mound's turns. When the mound\
      \ moves, the engulfed creature moves with them. An engulfed creature can try\
      \ to escape by taking an action to make a DC 10 plus PB Strength check. On a\
      \ success, that creature is freed and shunted to an unoccupied space of their\
      \ choice within 5 feet of the mound.\n\nThe mound can have one Large or up to\
      \ four Medium or smaller creatures engulfed at a time."
    "name": "5th Level: Engulf (8 Ferocity)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/plant/token/shambling-mound-companion-fleemortals.png"
```
^statblock
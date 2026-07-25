---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/plant/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Shambling Mound
---
# [Shambling Mound](3-Mechanics\CLI\bestiary\plant/shambling-mound-fleemortals.md)
*Source: Flee, Mortals! p. 224*  

```statblock
"name": "Shambling Mound (FleeMortals)"
"size": "Gargantuan"
"type": "plant"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "155"
"hit_dice": "10d20 + 50"
"modifier": !!int "-2"
"stats":
  - !!int "20"
  - !!int "7"
  - !!int "20"
  - !!int "5"
  - !!int "10"
  - !!int "8"
"speed": "20 ft."
"saves":
  - "constitution": !!int "8"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 120 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The mound has a vegetative sack on their body where they carry engulfed\
      \ creatures. The sack can be attacked (AC 15; 50 hit points; immunity to poison\
      \ and psychic damage), which deals no damage to the mound. Destroying the sack\
      \ frees creatures trapped by the mound's Engulf action. The mound regrows the\
      \ sack at the beginning of their next turn."
    "name": "Engulfing Sack"
  - "desc": "While the mound remains motionless, they are indistinguishable from an\
      \ ordinary mass of vegetation."
    "name": "False Appearance"
"actions":
  - "desc": "The mound makes two Vine Lash attacks. They can replace one attack with\
      \ a use of Engulf, if available."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 60\
      \ ft., one target. Hit: 14 (2d8 + 5) piercing damage. If the target is Medium\
      \ or smaller, the mound can pull the target up to 30 feet toward them."
    "name": "Vine Lash"
  - "desc": "The mound reaches out with writhing vines and attempts to pull in up\
      \ to two Medium or smaller creatures within 30 feet of them. Each target must\
      \ succeed on a DC 16 Strength saving throw or be engulfed in the mound's engulfing\
      \ sack. An engulfed creature is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ has total cover against attacks and other effects outside the mound, and takes\
      \ 7 (2d6) poison damage at the start of each of the mound's turns. When the\
      \ mound moves, the engulfed creature moves with them. If the mound dies or their\
      \ engulfing sack is destroyed, each engulfed creature is freed and shunted to\
      \ an unoccupied space of their choice within 5 feet of the mound."
    "name": "Engulf (Recharge 5-6)"
"reactions":
  - "desc": "When the mound takes damage, the inside of their engulfing sack churns\
      \ with poison. Each creature engulfed by the mound takes 3 (d6) poison damage,\
      \ and the mound regains a number of hit points equal to the total damage dealt\
      \ by this reaction to creatures in their sack."
    "name": "Poison Froth"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/plant/token/shambling-mound-fleemortals.png"
```
^statblock
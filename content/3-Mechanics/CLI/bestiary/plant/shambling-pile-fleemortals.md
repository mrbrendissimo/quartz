---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Shambling Pile
---
# [Shambling Pile](3-Mechanics\CLI\bestiary\plant/shambling-pile-fleemortals.md)
*Source: Flee, Mortals! p. 225*  

```statblock
"name": "Shambling Pile (FleeMortals)"
"size": "Medium"
"type": "plant"
"subtype": "Minion"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "12"
"modifier": !!int "-2"
"stats":
  - !!int "16"
  - !!int "7"
  - !!int "16"
  - !!int "5"
  - !!int "10"
  - !!int "5"
"speed": "20 ft."
"damage_immunities": "poison"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "While the pile remains motionless, they are indistinguishable from an\
      \ ordinary mass of vegetation."
    "name": "False Appearance"
  - "desc": "If an enemy starts their turn within 5 feet of three or more piles, the\
      \ creature must succeed on a Dexterity saving throw or be [grappled](/3-Mechanics/CLI/conditions.md#Grappled).\
      \ While [grappled](/3-Mechanics/CLI/conditions.md#Grappled) in this way, the\
      \ target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained), and at\
      \ the start of each of the target's turns, they take poison damage equal to\
      \ the number of piles within 5 feet of them. The saving throw and escape DC\
      \ equal 10 plus the number of piles within 5 feet of the creature. The grapple\
      \ ends if fewer than three piles are within 5 feet of the creature."
    "name": "Hungry Grab"
  - "desc": "If the pile takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the pile takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 4 piercing\
      \ damage."
    "name": "Vine Lash (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock
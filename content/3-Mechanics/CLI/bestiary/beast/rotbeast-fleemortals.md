---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Rotbeast
---
# [Rotbeast](3-Mechanics\CLI\bestiary\beast/rotbeast-fleemortals.md)
*Source: Flee, Mortals! p. 304*  

```statblock
"name": "Rotbeast (FleeMortals)"
"size": "Large"
"type": "beast"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "76"
"hit_dice": "9d10 + 27"
"modifier": !!int "-1"
"stats":
  - !!int "19"
  - !!int "8"
  - !!int "16"
  - !!int "2"
  - !!int "12"
  - !!int "5"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "passive Perception 11"
"languages": ""
"cr": "3"
"traits":
  - "desc": "When the rotbeast dies, they release a burst of infectious air. Each\
      \ non-Fungus creature within 5 feet of them must succeed on a DC 13 Constitution\
      \ saving throw or gain a level of [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)\
      \ and become infected with forest rot disease. An infected creature regains\
      \ half the normal number of hit points when they spend Hit Dice or finish a\
      \ long rest, and they can't reduce their [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)\
      \ level by finishing a long rest.\n\nEach time a creature with forest rot finishes\
      \ a long rest, they must make a DC 13 Constitution saving throw. On a failed\
      \ save, the creature gains another level of [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion).\
      \ On a successful save, the creature loses a level of [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion).\n\
      \nIf a successful saving throw reduces the infected creature's level of [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)\
      \ below 1, the creature recovers from the disease."
    "name": "Forest Rot"
  - "desc": "When the rotbeast leaves a space, it becomes difficult terrain for creatures\
      \ other than rotbeasts for 24 hours. When a non-Fungus creature enters that\
      \ space for the first time on a turn or starts their turn there, they must make\
      \ a DC 13 Constitution saving throw, taking 3 (d6) poison damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Rotwake"
"actions":
  - "desc": "The rotbeast makes two attacks using Weakening Horns, Rotting Hooves,\
      \ or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
      \ (2d8 + 4) piercing damage, and the target has disadvantage on Constitution\
      \ saving throws until the end of their next turn."
    "name": "Weakening Horns"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 9\
      \ (2d4 + 4) bludgeoning damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or contract forest rot."
    "name": "Rotting Hooves"
"bonus_actions":
  - "desc": "The rotbeast regains 3 (d6) hit points for each creature within 60 feet\
      \ of them infected with forest rot."
    "name": "Healing Rot (1/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/rotbeast-fleemortals.png"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Fire Giant Trooper
---
# [Fire Giant Trooper](3-Mechanics\CLI\bestiary\giant/fire-giant-trooper-fleemortals.md)
*Source: Flee, Mortals! p. 107*  

```statblock
"name": "Fire Giant Trooper (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Minion"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "19"
"modifier": !!int "2"
"stats":
  - !!int "22"
  - !!int "14"
  - !!int "19"
  - !!int "10"
  - !!int "14"
  - !!int "13"
"speed": "40 ft."
"damage_immunities": "fire"
"senses": "passive Perception 12"
"languages": "Giant"
"cr": "12"
"traits":
  - "desc": "If the trooper takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the trooper takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "The first time a creature other than a fire giant touches the trooper\
      \ or hits them with a melee attack on a turn, that creature takes 7 fire damage."
    "name": "Molten Flesh"
"actions":
  - "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 3\
      \ bludgeoning damage plus 3 fire damage, and the target must succeed on a Strength\
      \ saving throw or fall [prone](/3-Mechanics/CLI/conditions.md#Prone). The DC\
      \ for this saving throw equals 12 + the number of troopers who joined the group\
      \ attack."
    "name": "Unarmed Strike (Group Attack)"
  - "desc": "Ranged Weapon Attack: +10 to hit, range 60/240 ft., one target. Hit:\
      \ 6 bludgeoning damage."
    "name": "Rock (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock
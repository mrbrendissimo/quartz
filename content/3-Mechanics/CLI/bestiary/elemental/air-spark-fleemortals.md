---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/elemental/air
- ttrpg-cli/monster/type/elemental/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Air Spark
---
# [Air Spark](3-Mechanics\CLI\bestiary\elemental/air-spark-fleemortals.md)
*Source: Flee, Mortals! p. 89*  

```statblock
"name": "Air Spark (FleeMortals)"
"size": "Small"
"type": "elemental"
"subtype": "air, Minion"
"alignment": "Any alignment"
"ac": !!int "13"
"hp": !!int "22"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "10"
  - !!int "9"
  - !!int "11"
  - !!int "12"
"speed": "20 ft., fly 50 ft. (hover)"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Auran, Common"
"cr": "15"
"traits":
  - "desc": "If the spark takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the spark takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Spell Attack: +8 to hit, reach 5 ft., one target. Hit: 8 slashing\
      \ damage, and if this attack was made by more than one air spark against a Large\
      \ or smaller creature, the sparks can move that creature up to 5 feet horizontally\
      \ for each spark that joined the attack."
    "name": "Wind Sweep (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock
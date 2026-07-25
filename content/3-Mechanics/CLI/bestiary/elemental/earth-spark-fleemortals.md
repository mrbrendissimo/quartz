---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/earth
- ttrpg-cli/monster/type/elemental/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Earth Spark
---
# [Earth Spark](3-Mechanics\CLI\bestiary\elemental/earth-spark-fleemortals.md)
*Source: Flee, Mortals! p. 91*  

```statblock
"name": "Earth Spark (FleeMortals)"
"size": "Large"
"type": "elemental"
"subtype": "earth, Minion"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "17"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "16"
  - !!int "9"
  - !!int "10"
  - !!int "12"
"speed": "30 ft., burrow 20 ft."
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Terran"
"cr": "10"
"traits":
  - "desc": "If the spark takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the spark takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "If an enemy who is touching the ground starts their turn within 5 feet\
      \ of two or more earth sparks, the enemy must make a Strength saving throw with\
      \ a DC equal to 12 plus the number of earth sparks within 5 feet of the enemy.\
      \ On a failed save, the enemy falls [prone](/3-Mechanics/CLI/conditions.md#Prone),\
      \ and they can't stand up until there are fewer than two earth sparks within\
      \ 5 feet of them."
    "name": "Trampling Rampage"
"actions":
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 5 bludgeoning\
      \ damage."
    "name": "Shatter Smash (Group Attack)"
  - "desc": "Ranged Weapon Attack: +7 to hit, range 30/60 ft., one target. Hit:\
      \ 5 bludgeoning damage. If the target is a flying creature, they must succeed\
      \ on a Strength saving throw or fall [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ The DC for this saving throw equals 12 plus the number of sparks who joined\
      \ the attack."
    "name": "Snort Rocks (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock
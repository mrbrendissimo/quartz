---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/artillery
statblock: inline
statblock-link: "#^statblock"
aliases:
- Frost Giant Storm Hurler
---
# [Frost Giant Storm Hurler](3-Mechanics\CLI\bestiary\giant/frost-giant-storm-hurler-fleemortals.md)
*Source: Flee, Mortals! p. 108*  

```statblock
"name": "Frost Giant Storm Hurler (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Artillery"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "issenblau plating"
"hp": !!int "105"
"hit_dice": "10d12 + 40"
"modifier": !!int "-1"
"stats":
  - !!int "22"
  - !!int "9"
  - !!int "18"
  - !!int "9"
  - !!int "10"
  - !!int "11"
"speed": "40 ft., climb 30 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"damage_immunities": "cold"
"senses": "passive Perception 13"
"languages": "Giant"
"cr": "8"
"traits":
  - "desc": "Wisps of stinging snow and icy winds surround the storm hurler. When\
      \ an enemy [concentrating](/3-Mechanics/CLI/conditions.md#Concentration) on\
      \ a power, a spell, or a similar effect starts their turn within 15 feet of\
      \ the storm hurler, the enemy must succeed on a DC 15 Constitution saving throw\
      \ or lose [concentration](/3-Mechanics/CLI/conditions.md#Concentration)."
    "name": "Oncoming Storm"
"actions":
  - "desc": "The storm hurler makes two Ice Javelin attacks."
    "name": "Multiattack"
  - "desc": "Ranged Weapon Attack: +9 to hit, range 120/360 ft., one target. Hit:\
      \ 22 (3d10 + 6) piercing damage, and the target's speed is reduced by 10 feet\
      \ until the end of their next turn."
    "name": "Ice Javelin"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 28\
      \ (4d10 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "The storm hurler throws up to three Medium ice javelins, each at an unoccupied\
      \ space they can see within 300 feet of them. These spaces must be within 30\
      \ feet of each other. The javelins have AC 13, 10 hit points, and vulnerability\
      \ to fire damage. At the start of the storm hurler's next turn, any javelins\
      \ with hit points remaining explode, showering icicles in a 20-foot radius.\
      \ Creatures within the area of one or more explosions must make a DC 17 Dexterity\
      \ saving throw. On a failed save, a creature takes 28 (8d6) cold damage and\
      \ is [restrained](/3-Mechanics/CLI/conditions.md#Restrained) for 1 minute (save\
      \ ends at end of turn). On a successful save, a creature takes half as much\
      \ damage and isn't [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ Objects within this area take 28 (8d6) cold damage."
    "name": "Flower of Frost (3/Day)"
"reactions":
  - "desc": "When a creature within 120 feet of the storm hurler misses them with\
      \ a ranged weapon attack, the storm hurler can manipulate the storm surrounding\
      \ them to freeze the projectile and hurl it back at the attacker as an Ice Javelin\
      \ attack."
    "name": "Frozen Retribution"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/giant/token/frost-giant-storm-hurler-fleemortals.png"
```
^statblock
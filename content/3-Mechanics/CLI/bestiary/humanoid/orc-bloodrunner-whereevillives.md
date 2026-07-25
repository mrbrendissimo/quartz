---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/orc
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Orc Bloodrunner
---
# [Orc Bloodrunner](3-Mechanics\CLI\bestiary\humanoid/orc-bloodrunner-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 40, Flee, Mortals! p. 206*  

```statblock
"name": "Orc Bloodrunner (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Skirmisher"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[spiked shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "15"
"hit_dice": "2d8 + 6"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "9"
  - !!int "10"
"speed": "60 ft."
"saves":
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Orc"
"cr": "1/2"
"traits":
  - "desc": "When the bloodrunner isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ and they are reduced to 0 hit points but not killed outright, they can make\
      \ an attack against an enemy (no action required) before the hit point reduction\
      \ is resolved. If the attack hits and its damage reduces the target to 0 hit\
      \ points, the bloodrunner drops to 1 hit point instead of 0 hit points."
    "name": "Relentless (1/Turn)"
  - "desc": "The bloodrunner can occupy a [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ creature's space. The first time the bloodrunner enters a [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ creature's space on the bloodrunner's turn, the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ creature takes 3 (d6) bludgeoning damage. When a [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ creature in the bloodrunner's space stands up, the creature enters the nearest\
      \ unoccupied space of their choice."
    "name": "Unimpeded"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
      \ + 3) piercing damage. If the bloodrunner moves at least 10 feet before hitting\
      \ a Large or smaller creature with this attack, the bloodrunner can choose to\
      \ knock the target [prone](/3-Mechanics/CLI/conditions.md#Prone) or push them\
      \ up to 10 feet away."
    "name": "Spiked Shield"
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. Hit: 5 (1d6 + 2) piercing damage."
    "name": "Javelin"
"reactions":
  - "desc": "When the bloodrunner makes a Dexterity saving throw, they can gain advantage\
      \ on the save. To do so, the bloodrunner can't be [prone](/3-Mechanics/CLI/conditions.md#Prone),\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), or [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Juke"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
```
^statblock
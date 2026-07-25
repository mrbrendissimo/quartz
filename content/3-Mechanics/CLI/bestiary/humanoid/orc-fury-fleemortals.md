---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/brute
- ttrpg-cli/monster/type/humanoid/orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- Orc Fury
---
# [Orc Fury](3-Mechanics\CLI\bestiary\humanoid/orc-fury-fleemortals.md)
*Source: Flee, Mortals! p. 208*  

```statblock
"name": "Orc Fury (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Brute"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "16"
  - !!int "9"
  - !!int "11"
  - !!int "12"
"speed": "35 ft."
"saves":
  - "strength": !!int "5"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Orc"
"cr": "1/2"
"traits":
  - "desc": "When the fury isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ and they are reduced to 0 hit points but not killed outright, they can make\
      \ an attack against an enemy (no action required) before the hit point reduction\
      \ is resolved. If the attack hits and its damage reduces the target to 0 hit\
      \ points, the fury drops to 1 hit point instead of 0 hit points."
    "name": "Relentless (1/Turn)"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (1d12\
      \ + 3) slashing damage, or 12 (1d12 + 6) slashing damage if the target is [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ If the target is a Medium or smaller creature, they must succeed on a DC 13\
      \ Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Haymaker Greataxe"
  - "desc": "Melee  or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. Hit: 6 (1d6 + 3) piercing damage."
    "name": "Javelin"
"bonus_actions":
  - "desc": "The fury regains 5 hit points."
    "name": "Healing Rally (1/Day)"
"source":
  - "FleeMortals"
```
^statblock
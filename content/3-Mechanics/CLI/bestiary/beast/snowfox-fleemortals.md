---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/beast/ambusher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Snowfox
---
# [Snowfox](3-Mechanics\CLI\bestiary\beast/snowfox-fleemortals.md)
*Source: Flee, Mortals! p. 41*  

```statblock
"name": "Snowfox (FleeMortals)"
"size": "Tiny"
"type": "beast"
"subtype": "Ambusher"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "13"
"hit_dice": "3d4 + 6"
"modifier": !!int "3"
"stats":
  - !!int "5"
  - !!int "16"
  - !!int "14"
  - !!int "6"
  - !!int "12"
  - !!int "10"
"speed": "30 ft., burrow 10 ft., fly 30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+3"
"damage_resistances": "cold"
"senses": "darkvision 120 ft., tremorsense 15 ft., passive Perception 15"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The snowfox has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ checks made in snowy terrain or cloudy skies."
    "name": "Natural Camouflage"
  - "desc": "The snowfox doesn't provoke opportunity attacks when they leave an enemy's\
      \ reach."
    "name": "Nimble Escape"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 4 piercing\
      \ damage, and the snowfox attaches to the target. While attached, the snowfox's\
      \ Claw attacks against that target are made with advantage, and the snowfox\
      \ can't attack another target. The target or a creature who can reach them can\
      \ detach the snowfox as an action with a successful DC 13 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ check. The snowfox can detach by spending 5 feet of their movement."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 4 slashing\
      \ damage."
    "name": "Claw"
"bonus_actions":
  - "desc": "The snowfox burrows up to 5 feet in snow."
    "name": "Burrow"
  - "desc": "The snowfox makes a Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ check."
    "name": "Listen"
"source":
  - "FleeMortals"
```
^statblock
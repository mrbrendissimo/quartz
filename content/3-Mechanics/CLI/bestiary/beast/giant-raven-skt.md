---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- Giant Raven
---
# [Giant Raven](3-Mechanics\CLI\bestiary\beast/giant-raven-skt.md)
*Source: Storm King's Thunder p. 66*  

```statblock
"name": "Giant Raven (SKT)"
"size": "Large"
"type": "beast"
"alignment": "Neutral Evil"
"ac": !!int "10"
"hp": !!int "22"
"hit_dice": "3d10 + 6"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "15"
  - !!int "6"
  - !!int "12"
  - !!int "7"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "understands Common but can't speak"
"cr": "1"
"traits":
  - "desc": "The raven has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on sight or smell."
    "name": "Keen Sight and Smell"
  - "desc": "The raven has advantage on an attack roll against a creature if at least\
      \ one of the raven's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The raven makes two attacks: one with its beak and one with its talons."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
      \ + 2) piercing damage."
    "name": "Beak"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
      \ + 2) slashing damage."
    "name": "Talons"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/beast/token/giant-raven-skt.webp"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Braxow
---
# [Braxow](3-Mechanics\CLI\bestiary\npc/braxow-skt.md)
*Source: Storm King's Thunder p. 207*  

```statblock
"name": "Braxow (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"modifier": !!int "2"
"stats":
  - !!int "23"
  - !!int "15"
  - !!int "20"
  - !!int "10"
  - !!int "12"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "8"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Giant"
"cr": "7"
"traits":
  - "desc": "The giant has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ checks made to hide in rocky terrain."
    "name": "Stone Camouflage"
"actions":
  - "desc": "The giant makes two greatclub attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 19\
      \ (3d8 + 6) bludgeoning damage."
    "name": "Greatclub"
  - "desc": "Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. Hit:\
      \ 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 17 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Rock"
"reactions":
  - "desc": "If a rock or similar object is hurled at the giant, the giant can, with\
      \ a successful DC 10 Dexterity saving throw, catch the missile and take no bludgeoning\
      \ damage from it."
    "name": "Rock Catching"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/braxow-skt.webp"
```
^statblock
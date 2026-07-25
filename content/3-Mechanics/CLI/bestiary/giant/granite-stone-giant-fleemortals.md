---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/soldier
statblock: inline
statblock-link: "#^statblock"
aliases:
- Granite Stone Giant
---
# [Granite Stone Giant](3-Mechanics\CLI\bestiary\giant/granite-stone-giant-fleemortals.md)
*Source: Flee, Mortals! p. 111*  

```statblock
"name": "Granite Stone Giant (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Soldier"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"modifier": !!int "2"
"stats":
  - !!int "23"
  - !!int "15"
  - !!int "21"
  - !!int "12"
  - !!int "15"
  - !!int "12"
"speed": "40 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks that aren't\
  \ adamantine"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Giant"
"cr": "7"
"traits":
  - "desc": "While motionless, the giant is indistinguishable from a statue."
    "name": "False Appearance"
  - "desc": "When a creature attacks the giant with a melee weapon that isn't adamantine\
      \ and rolls a 1 on the d20 for that attack, that weapon is destroyed if it is\
      \ mundane. If that weapon is supernatural, it loses all supernatural properties\
      \ for 1 hour."
    "name": "Stone Flesh"
"actions":
  - "desc": "The giant makes two Greatclub attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 19\
      \ (3d8 + 6) bludgeoning damage. If the same creature is hit twice with this\
      \ attack on a turn, they have disadvantage on attack rolls until the end of\
      \ their next turn."
    "name": "Greatclub"
  - "desc": "Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. Hit:\
      \ 28 (4d10 + 6) bludgeoning damage, and the target must succeed on a DC 17 Strength\
      \ saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Rock"
"source":
  - "FleeMortals"
```
^statblock
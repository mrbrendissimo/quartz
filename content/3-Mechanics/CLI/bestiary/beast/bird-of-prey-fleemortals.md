---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/unknown
- ttrpg-cli/monster/type/beast/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bird of Prey
---
# [Bird of Prey](3-Mechanics\CLI\bestiary\beast/bird-of-prey-fleemortals.md)
*Source: Flee, Mortals! p. 37*  

```statblock
"name": "Bird of Prey (FleeMortals)"
"size": "Unknown"
"type": "beast"
"subtype": "Skirmisher"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "18"
"hit_dice": "4d6 + 4"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "12"
  - !!int "4"
  - !!int "12"
  - !!int "5"
"speed": "10 ft., fly 80 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The bird has a +10 bonus to Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Exceptional Vision"
  - "desc": "The bird doesn't provoke opportunity attacks when they fly out of an\
      \ enemy's reach."
    "name": "Flyby"
  - "desc": "If the bird descends at least 30 feet on their turn, they can take the\
      \ Dash action as a bonus action. When they do, they have advantage on the next\
      \ attack they make before the end of their turn."
    "name": "High-Speed Dive (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
      \ + 3) piercing damage."
    "name": "Beak"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
      \ + 3) slashing damage. If the target is a Tiny creature, they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 12). If the target is a Small or larger creature, the bird attaches\
      \ to them. While attached, the bird's Beak attacks against that target are made\
      \ with advantage, and the bird can't attack another target. The target or a\
      \ creature who can reach them can attempt to detach the bird as an action by\
      \ making a DC 12 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ check. On a failed check, the attached target takes 2 (d4) slashing damage.\
      \ On a successful check, the attached target takes 2 (d4) slashing damage and\
      \ is no longer attached. The bird can detach by spending 5 feet of their movement."
    "name": "Talons"
"bonus_actions":
  - "desc": "The bird makes a Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ check."
    "name": "Spot"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/bird-of-prey-fleemortals.png"
```
^statblock
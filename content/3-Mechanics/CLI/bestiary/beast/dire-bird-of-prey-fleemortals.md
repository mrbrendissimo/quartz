---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/unknown
- ttrpg-cli/monster/type/beast/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Dire Bird of Prey
---
# [Dire Bird of Prey](3-Mechanics\CLI\bestiary\beast/dire-bird-of-prey-fleemortals.md)
*Source: Flee, Mortals! p. 37*  

```statblock
"name": "Dire Bird of Prey (FleeMortals)"
"size": "Unknown"
"type": "beast"
"subtype": "Skirmisher"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d10 + 24"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "16"
  - !!int "6"
  - !!int "12"
  - !!int "5"
"speed": "20 ft., fly 90 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": ""
"cr": "3"
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
  - "desc": "The bird makes two attacks using Heavy Beak, Rending Talons, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
      \ + 3) piercing damage. On a critical hit, the target is [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the start of the bird's next turn."
    "name": "Heavy Beak"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
      \ + 3) slashing damage. If the target is Medium or smaller, they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 13). While grappling a target, the bird's Beak attacks against\
      \ that target are made with advantage, and the bird can't attack another target.\
      \ Each time the target makes a check to end the grapple, the target takes 4\
      \ (d8) slashing damage."
    "name": "Rending Talons"
  - "desc": "The bird's powerful talons crush a [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ target. The target must make a DC 13 Strength saving throw, taking 17 (5d6)\
      \ bludgeoning damage on a failed save, or half as much damage on a successful\
      \ one. If the target fails the save by 5 or more, they are also [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the end of their next turn."
    "name": "Crushing Grip"
"bonus_actions":
  - "desc": "The bird makes a Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ check."
    "name": "Spot"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/dire-bird-of-prey-fleemortals.png"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/bugbear
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bugbear Commander
---
# [Bugbear Commander](3-Mechanics\CLI\bestiary\humanoid/bugbear-commander-fleemortals.md)
*Source: Flee, Mortals! p. 51*  

```statblock
"name": "Bugbear Commander (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "bugbear, Support"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "15"
  - !!int "17"
  - !!int "14"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Goblin"
"cr": "5"
"traits":
  - "desc": "Allied Humanoids within 30 feet of the commander who can see or hear\
      \ them have advantage on Wisdom and Charisma saving throws and gain a +1 bonus\
      \ to weapon attack and damage rolls."
    "name": "Commander's Inspiration"
"actions":
  - "desc": "The commander makes two Greatsword or two Longbow attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
      \ (2d6 + 4) slashing damage, and one ally within 30 feet of the target who can\
      \ see the commander has advantage on their next melee attack roll made against\
      \ the target before the start of the commander's next turn."
    "name": "Greatsword"
  - "desc": "Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. Hit:\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
  - "desc": "Each ally within 60 feet of the commander who can hear and understand\
      \ them can use a reaction to move up to their speed and make a weapon attack."
    "name": "Bark Orders (Recharge 6)"
"reactions":
  - "desc": "When another creature within 60 feet of the commander who can hear and\
      \ understand them makes a saving throw, the commander can give that creature\
      \ advantage on the saving throw."
    "name": "Bolstering Pride"
"source":
  - "FleeMortals"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hill Giant Clobberer
---
# [Hill Giant Clobberer](3-Mechanics\CLI\bestiary\giant/hill-giant-clobberer-fleemortals.md)
*Source: Flee, Mortals! p. 109*  

```statblock
"name": "Hill Giant Clobberer (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Brute"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "12d12 + 48"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "8"
  - !!int "18"
  - !!int "8"
  - !!int "9"
  - !!int "7"
"speed": "30 ft., climb 20 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Giant"
"cr": "5"
"traits":
  - "desc": "When the clobberer targets a creature with an attack, another creature\
      \ within range of that attack can use their reaction to distract the clobberer.\
      \ If the clobberer can see or hear the distracting creature, the clobberer targets\
      \ them with the attack instead."
    "name": "Distracted"
  - "desc": "When the clobberer hits a [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ creature with a melee weapon attack, the attack deals an extra 10 (3d6) damage,\
      \ and that target's speed is reduced to 0 until the end of their next turn."
    "name": "Pummel"
  - "desc": "The clobberer's attacks deal double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The clobberer makes two attacks using Greatclub, Rock, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 18\
      \ (3d8 + 5) bludgeoning damage, and the target must succeed on a DC 16 Strength\
      \ saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Greatclub"
  - "desc": "Ranged Weapon Attack: +8 to hit, range 60/240 ft., one target. Hit:\
      \ 16 (2d10 + 5) bludgeoning damage."
    "name": "Rock"
"bonus_actions":
  - "desc": "The clobberer falls [prone](/3-Mechanics/CLI/conditions.md#Prone), and\
      \ each creature on the ground within 20 feet of the clobberer must succeed on\
      \ a DC 16 Dexterity saving throw or fall [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ Structures in that area take 33 (6d10) bludgeoning damage."
    "name": "Hill Quake"
"source":
  - "FleeMortals"
```
^statblock
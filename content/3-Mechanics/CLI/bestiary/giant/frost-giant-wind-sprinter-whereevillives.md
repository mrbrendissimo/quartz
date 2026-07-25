---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Frost Giant Wind Sprinter
---
# [Frost Giant Wind Sprinter](3-Mechanics\CLI\bestiary\giant/frost-giant-wind-sprinter-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 233, Flee, Mortals! p. 109*  

```statblock
"name": "Frost Giant Wind Sprinter (WhereEvilLives)"
"size": "Huge"
"type": "giant"
"subtype": "Skirmisher"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "issenblau plating"
"hp": !!int "115"
"hit_dice": "11d12 + 44"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "9"
  - !!int "18"
  - !!int "9"
  - !!int "10"
  - !!int "10"
"speed": "60 ft., climb 30 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"damage_immunities": "cold"
"senses": "passive Perception 13"
"languages": "Giant"
"cr": "8"
"traits":
  - "desc": "When the wind sprinter enters a Medium or smaller enemy's space, the\
      \ enemy must choose to either fall [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ or take 10 (3d6) bludgeoning damage. Each enemy can be affected by this trait\
      \ only once per turn."
    "name": "Crush Underfoot"
  - "desc": "Wisps of stinging snow and icy winds surround the wind sprinter. When\
      \ an enemy [concentrating](/3-Mechanics/CLI/conditions.md#Concentration) on\
      \ a power, a spell, or a similar effect starts their turn within 15 feet of\
      \ the wind sprinter, the enemy must succeed on a DC 15 Constitution saving throw\
      \ or lose [concentration](/3-Mechanics/CLI/conditions.md#Concentration)."
    "name": "Oncoming Storm"
"actions":
  - "desc": "The wind sprinter makes two Ice Axe attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 22\
      \ (3d10 + 6) slashing damage."
    "name": "Ice Axe"
  - "desc": "Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. Hit:\
      \ 28 (4d10 + 6) bludgeoning damage."
    "name": "Rock"
  - "desc": "The wind sprinter moves up to their speed in a straight line. At any\
      \ point during this move, they can make up to three Ice Axe attacks against\
      \ different creatures."
    "name": "Blizzard Surge (Recharge 5-6)"
"reactions":
  - "desc": "After a Medium or smaller creature makes an opportunity attack against\
      \ the wind sprinter, the wind sprinter can make an Ice Axe attack against that\
      \ creature."
    "name": "Begone, Smallfolk!"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
```
^statblock
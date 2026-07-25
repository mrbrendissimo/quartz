---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/soldier
statblock: inline
statblock-link: "#^statblock"
aliases:
- Human Knave
---
# [Human Knave](3-Mechanics\CLI\bestiary\humanoid/human-knave-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 162*  

```statblock
"name": "Human Knave (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Soldier"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[breastplate](/3-Mechanics/CLI/items/breastplate-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "When the knave makes an attack, they have advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
"actions":
  - "desc": "The knave makes two Morningstar or two Javelin attacks. They can replace\
      \ one attack with a Shield Bash attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
      \ + 4) piercing damage, or 13 (2d8 + 4) piercing damage if the target is [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Morningstar"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4\
      \ + 4) bludgeoning damage, and if the target is a Medium or smaller creature,\
      \ they must succeed on a DC 14 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Shield Bash"
  - "desc": "Ranged Weapon Attack: +6 to hit, range 30/120 ft., one target. Hit:\
      \ 7 (1d6 + 4) piercing damage."
    "name": "Javelin"
"bonus_actions":
  - "desc": "The knave kicks one [prone](/3-Mechanics/CLI/conditions.md#Prone) creature\
      \ within 5 feet of them. The target must succeed on a DC 14 Constitution saving\
      \ throw or their speed is reduced to 0 until the end of their next turn."
    "name": "Stay Down"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/human-knave-fleemortals.png"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/orc
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Orc Godcaller
---
# [Orc Godcaller](3-Mechanics\CLI\bestiary\humanoid/orc-godcaller-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 209*  

```statblock
"name": "Orc Godcaller (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Support"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "16"
  - !!int "12"
  - !!int "13"
  - !!int "19"
"speed": "35 ft."
"saves":
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+3"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+8"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Orc"
"cr": "4"
"traits":
  - "desc": "When the godcaller isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ and they are reduced to 0 hit points but not killed outright, they can make\
      \ an attack against an enemy (no action required) before the hit point reduction\
      \ is resolved. If the attack hits and its damage reduces the target to 0 hit\
      \ points, the godcaller drops to 1 hit point instead of 0 hit points."
    "name": "Relentless (1/Turn)"
"actions":
  - "desc": "Melee  or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 30 ft.,\
      \ one creature who can hear the godcaller. Hit: 18 (4d6 + 4) thunder damage."
    "name": "Power Chord (1st-Level Spell)"
  - "desc": "The godcaller chooses another creature within 30 feet of them. If the\
      \ target can hear the godcaller, the target can use their reaction to move up\
      \ to their speed and make an attack."
    "name": "Cadenza"
  - "desc": "The godcaller and each ally within 30 feet of them who can hear them\
      \ has advantage on attack rolls until the start of the godcaller's next turn.\
      \ This effect ends early if the godcaller takes any damage."
    "name": "Song of the Gods (2nd-Level Spell)"
"bonus_actions":
  - "desc": "The godcaller and up to three allies within 60 feet of them who can hear\
      \ them regain 20 hit points, and these creatures ignore difficult terrain for\
      \ 1 minute."
    "name": "Rallying Ostinato (1/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/orc-godcaller-fleemortals.png"
```
^statblock
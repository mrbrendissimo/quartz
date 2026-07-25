---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/ambusher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lamasombra
---
# [Lamasombra](3-Mechanics\CLI\bestiary\monstrosity/lamasombra-fleemortals.md)
*Source: Flee, Mortals! p. 296*  

```statblock
"name": "Lamasombra (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Ambusher"
"alignment": "Unaligned"
"ac": !!int "16"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"modifier": !!int "6"
"stats":
  - !!int "18"
  - !!int "22"
  - !!int "19"
  - !!int "7"
  - !!int "14"
  - !!int "8"
"speed": "60 ft., climb 60 ft."
"saves":
  - "dexterity": !!int "11"
  - "constitution": !!int "9"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+16"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+7"
"senses": "blindsight 120 ft., passive Perception 17"
"languages": ""
"cr": "13"
"traits":
  - "desc": "The lamasombra's unnatural scales, padded feet, and bones allow them\
      \ to avoid detection. They can't be detected with tremorsense. When the lamasombra\
      \ is in darkness or dim light, they are [invisible](/3-Mechanics/CLI/conditions.md#Invisible)\
      \ to creatures with darkvision, but they are visible in dim light to creatures\
      \ without darkvision."
    "name": "Cave Apex"
  - "desc": "The lamasombra can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The lamasombra makes one Bite attack and one Tongue attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 33\
      \ (6d8 + 6) piercing damage. If the target is a creature, they must succeed\
      \ on a DC 17 Constitution saving throw or contract boiling wastes disease. Until\
      \ the disease is cured, the target can't regain hit points, and the lamasombra\
      \ can sense the direction to the creature's location as long as they're on the\
      \ same plane of existence."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 20 ft., one target. Hit: 27\
      \ (6d6 + 6) bludgeoning damage, or 37 (9d6 + 6) bludgeoning damage if the target\
      \ is a creature who can't see the lamasombra. If the target is a Large or smaller\
      \ creature, they are pulled up to 15 feet in a straight line toward the lamasombra."
    "name": "Tongue"
"bonus_actions":
  - "desc": "The lamasombra takes the Dash, Disengage, or Hide action."
    "name": "Nightmarish Cunning"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/lamasombra-fleemortals.png"
```
^statblock
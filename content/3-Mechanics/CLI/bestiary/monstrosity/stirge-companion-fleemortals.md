---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/monstrosity/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Stirge Companion
---
# [Stirge Companion](3-Mechanics\CLI\bestiary\monstrosity/stirge-companion-fleemortals.md)
*Source: Flee, Mortals! p. 227*  

```statblock
"name": "Stirge Companion (FleeMortals)"
"size": "Tiny"
"type": "monstrosity"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "3"
"stats":
  - !!int "5"
  - !!int "16"
  - !!int "14"
  - !!int "5"
  - !!int "14"
  - !!int "10"
"speed": "10 ft., fly 30 ft."
"saves":
  - "name": "Dexterity"
    "desc": "+3 plus PB"
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3 plus PB"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": ""
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Proboscis)"
  - "desc": "The stirge makes a signature attack. On a hit, the target also has disadvantage\
      \ on the next attack they make before the end of their next turn."
    "name": "1st Level: Destabilizing Attack (2 Ferocity)"
  - "desc": "The stirge makes a signature attack. On a hit, the target takes an extra\
      \ PBd4 piercing damage and is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the end of their next turn."
    "name": "3rd Level: Quick Drink (5 Ferocity)"
  - "desc": "The stirge makes a signature attack against a creature. On a hit, the\
      \ target takes an extra PBd6 piercing damage and the stirge attaches to the\
      \ target and enters their space. While attached, the stirge moves with the target\
      \ and can't attack any creature other than the target. If the stirge hits the\
      \ target with an attack while attached, the target takes an extra PBd6 piercing\
      \ damage. The stirge can use an action or bonus action to detach and move 5\
      \ feet into an unoccupied space without provoking opportunity attacks. The stirge\
      \ also detaches if they become [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
      \ or [restrained](/3-Mechanics/CLI/conditions.md#Restrained), or if they take\
      \ more than PB × 5 damage in a turn."
    "name": "5th Level: Attach (8 Ferocity)"
"bonus_actions":
  - "desc": "If the stirge's caregiver is within 5 feet of them and the stirge isn't\
      \ attached to another creature, the stirge pumps life essence into the caregiver's\
      \ veins. The caregiver regains 1d6 plus PB hit points."
    "name": "Essence Shared (2/Long Rest)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/stirge-companion-fleemortals.png"
```
^statblock
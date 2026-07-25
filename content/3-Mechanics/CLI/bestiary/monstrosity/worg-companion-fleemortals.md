---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Worg Companion
---
# [Worg Companion](3-Mechanics\CLI\bestiary\monstrosity/worg-companion-fleemortals.md)
*Source: Flee, Mortals! p. 133*  

```statblock
"name": "Worg Companion (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "15"
  - !!int "14"
  - !!int "7"
  - !!int "12"
  - !!int "10"
"speed": "50 ft."
"saves":
  - "name": "Strength"
    "desc": "+3 plus PB"
  - "name": "Dexterity"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1 plus PB"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"traits":
  - "desc": "While the worg's caregiver is mounted on the worg, opportunity attacks\
      \ against the worg or their caregiver are made with disadvantage. The worg's\
      \ caregiver can mount or dismount the worg by spending 5 feet of movement."
    "name": "Move as One"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Bite)"
  - "desc": "The worg makes a signature attack. On a hit, the attack deals an extra\
      \ PB damage, and the target can't take reactions until the start of the worg's\
      \ next turn."
    "name": "1st Level: Overwhelming Attack (2 Ferocity)"
  - "desc": "The worg moves up to their speed without provoking opportunity attacks.\
      \ During or at the end of this move, they can make a signature attack against\
      \ one target."
    "name": "3rd Level: Brutal Charge (5 Ferocity)"
  - "desc": "The worg makes signature attacks against PB creatures of their choice\
      \ within 5 feet of them. On a hit, a target is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "5th Level: Bite Rampage (8 Ferocity)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/worg-companion-fleemortals.png"
```
^statblock
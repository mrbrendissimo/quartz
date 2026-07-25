---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
statblock-link: "#^statblock"
aliases:
- Human Mercenary
---
# [Human Mercenary](3-Mechanics\CLI\bestiary\humanoid/human-mercenary-fleemortals.md)
*Source: Flee, Mortals! p. 166*  

```statblock
"name": "Human Mercenary (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "name": "Strength"
    "desc": "+PB"
  - "name": "Dexterity"
    "desc": "+PB"
  - "name": "Constitution"
    "desc": "+PB"
  - "name": "Intelligence"
    "desc": "+PB"
  - "name": "Wisdom"
    "desc": "+PB"
  - "name": "Charisma"
    "desc": "+PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+0 plus PB"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+0 plus PB"
"senses": "passive Perception 0"
"languages": "Common"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 10 ft., one target. Hit:\
      \ 1d10 plus PB slashing damage. Beginning at 7th level, the mercenary can make\
      \ this attack twice, instead of once, when they take the Attack action on their\
      \ turn."
    "name": "Signature Attack (Halberd)"
  - "desc": "As an action, the mercenary restores PBd8 hit points to a creature they\
      \ can see within 5 feet of them."
    "name": "3rd Level: Battlefield Medicine (3/Day)"
  - "desc": "The mercenary takes the Attack action, making each attack with advantage\
      \ and dealing an extra PBd4 slashing damage on a hit."
    "name": "5th Level: Exploit Opening (3/Day)"
  - "desc": "When a creature enters a space within the mercenary's reach, the mercenary\
      \ uses a reaction to make a signature attack with advantage against that creature.\
      \ If this attack hits, it deals an extra PBd6 slashing damage."
    "name": "7th Level: Halberd Master (3/Day)"
"source":
  - "FleeMortals"
```
^statblock
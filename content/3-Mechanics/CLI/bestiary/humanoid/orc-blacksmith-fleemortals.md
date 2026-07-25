---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/orc
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
statblock-link: "#^statblock"
aliases:
- Orc Blacksmith
---
# [Orc Blacksmith](3-Mechanics\CLI\bestiary\humanoid/orc-blacksmith-fleemortals.md)
*Source: Flee, Mortals! p. 214*  

```statblock
"name": "Orc Blacksmith (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "12"
  - !!int "12"
"speed": "35 ft."
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
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1 plus PB"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": "Common, Orc"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d10 plus PB bludgeoning damage. Beginning at 7th level, the blacksmith can\
      \ make this attack twice, instead of once, when they take the Attack action\
      \ on their turn."
    "name": "Signature Attack (Warhammer)"
  - "desc": "When the blacksmith isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ and they take damage but aren't killed outright, they can make an attack against\
      \ an enemy (no action required) before the hit point reduction is resolved.\
      \ If the attack hits, the blacksmith regains twice their PB hit points."
    "name": "3rd Level: Relentless Rush (3/Day)"
  - "desc": "As a bonus action, the blacksmith touches a piece of armor and fortifies\
      \ it. For the next 10 minutes, a creature wearing the armor gains a bonus to\
      \ their AC equal to half the blacksmith's PB."
    "name": "5th Level: Reinforce Armor (3/Day)"
  - "desc": "As a bonus action, the blacksmith touches a weapon and polishes it. For\
      \ 1 minute, the weapon is magical and deals an extra PB damage."
    "name": "7th Level: Fortify Weapon (3/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/orc-blacksmith-fleemortals.png"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/bugbear
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bugbear Warden
---
# [Bugbear Warden](3-Mechanics\CLI\bestiary\humanoid/bugbear-warden-fleemortals.md)
*Source: Flee, Mortals! p. 53*  

```statblock
"name": "Bugbear Warden (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "bugbear, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "10"
  - !!int "10"
  - !!int "12"
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
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1 plus PB"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3 plus PB"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+1 plus PB"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": "Common, Goblin"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +3 plus PB to hit, reach 5 ft. or range\
      \ 80/320 ft., one target. Hit: 2d6 plus PB piercing damage. Beginning at 7th\
      \ level, the warden can make this attack twice, instead of once, when they take\
      \ the Attack action on their turn."
    "name": "Signature Attack (Spiked Bow)"
  - "desc": "As an action, the warden makes a signature attack. On a hit, the target's\
      \ speed is reduced to 0 until the end of their next turn."
    "name": "3rd Level: Halting Shot (3/Day)"
  - "desc": "As a bonus action, the warden inspires each ally within 30 feet of them\
      \ who can hear them, granting them advantage on attack rolls until the start\
      \ of the warden's next turn."
    "name": "5th Level: Presence of Inspiration (3/Day)"
  - "desc": "As an action, the warden makes a signature attack. Each ally within 30\
      \ feet of them who can see them can use a reaction to make a weapon attack,\
      \ cast a cantrip with a casting time of 1 action, or manifest a 1st-order power\
      \ with a manifestation time of 1 action."
    "name": "7th Level: Enraged Barrage (1/Day)"
"source":
  - "FleeMortals"
```
^statblock
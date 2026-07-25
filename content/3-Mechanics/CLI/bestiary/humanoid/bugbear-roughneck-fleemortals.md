---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/brute
- ttrpg-cli/monster/type/humanoid/bugbear
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bugbear Roughneck
---
# [Bugbear Roughneck](3-Mechanics\CLI\bestiary\humanoid/bugbear-roughneck-fleemortals.md)
*Source: Flee, Mortals! p. 53*  

```statblock
"name": "Bugbear Roughneck (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "bugbear, Brute"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "15"
  - !!int "10"
  - !!int "13"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+3"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Goblin"
"cr": "1"
"traits":
  - "desc": "Allied Humanoids within 15 feet of the roughneck who can see or hear\
      \ them have advantage on Wisdom and Charisma saving throws."
    "name": "Bugbear's Inspiration"
"actions":
  - "desc": "The roughneck makes two Handaxe attacks."
    "name": "Multiattack (Battle Fury Only)"
  - "desc": "Melee  or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 6 (1d6 + 3) slashing damage."
    "name": "Handaxe"
  - "desc": "Each ally within 15 feet of the roughneck who can hear and understand\
      \ them gains advantage on attack rolls until the start of the roughneck's next\
      \ turn."
    "name": "Bugbear Battle Cry (1/Day)"
"bonus_actions":
  - "desc": "The roughneck enters a furious state that lasts for 1 minute. While in\
      \ this state, the roughneck can take the Multiattack action on their turn, and\
      \ they have resistance to bludgeoning, piercing, and slashing damage from mundane\
      \ attacks."
    "name": "Battle Fury (1/Day)"
"source":
  - "FleeMortals"
```
^statblock
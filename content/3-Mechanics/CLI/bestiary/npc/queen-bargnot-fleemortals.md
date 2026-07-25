---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblin
- ttrpg-cli/monster/type/humanoid/leader
statblock: inline
statblock-link: "#^statblock"
aliases:
- Queen Bargnot
---
# [Queen Bargnot](3-Mechanics\CLI\bestiary\npc/queen-bargnot-fleemortals.md)
*Source: Flee, Mortals! p. 131*  

```statblock
"name": "Queen Bargnot (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "goblin, Leader"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md),\
  \ [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "54"
"hit_dice": "12d6 + 12"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "17"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "13"
"speed": "30 ft., climb 20 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+3"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Goblin"
"cr": "3"
"traits":
  - "desc": "Queen Bargnot doesn't provoke opportunity attacks when she moves out\
      \ of an enemy's reach."
    "name": "Crafty"
  - "desc": "When Queen Bargnot fails a saving throw against a spell or other supernatural\
      \ effect, she can choose a willing creature within 30 feet of her. Queen Bargnot\
      \ succeeds on the saving throw, the creature is targeted with the same spell\
      \ or effect as if they were in her space, and they fail their saving throw automatically."
    "name": "Take My Pain (3/Day)"
"actions":
  - "desc": "Queen Bargnot makes three Shortsword attacks or two Shortbow attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
      \ + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. Hit:\
      \ 6 (1d6 + 3) piercing damage."
    "name": "Shortbow"
"bonus_actions":
  - "desc": "Queen Bargnot shouts for aid and d4 [goblin lackey](/3-Mechanics/CLI/bestiary/humanoid/goblin-lackey-fleemortals.md)s\
      \ appear in unoccupied spaces within 60 feet of her."
    "name": "Get In Here"
"reactions":
  - "desc": "When an ally Queen Bargnot can see within 30 feet of her is reduced to\
      \ 0 hit points, they are reduced to 1 hit point instead."
    "name": "No Dying!"
"legendary_actions":
  - "desc": "Queen Bargnot has three villain actions. She can take each action once\
      \ during an encounter after an enemy's turn.\n\nShe can take these actions in\
      \ any order but can use only one per round."
    "name": ""
  - "desc": "Each ally within 60 feet of Queen Bargnot who can hear her can move up\
      \ to their speed or make a melee weapon attack (no action required)."
    "name": "Action 1: What Are You Waiting For?!"
  - "desc": "Queen Bargnot chooses an enemy she can see with 60 feet of her. Queen\
      \ Bargnot and each ally within 60 feet of her who can hear her can move up to\
      \ their speed toward the target."
    "name": "Action 2: Focus Fire"
  - "desc": "Each ally within 60 feet of Queen Bargnot who can hear her can make a\
      \ weapon attack with advantage (no action required). If the attack hits, it\
      \ deals an extra 3 (d6) damage."
    "name": "Action 3: Kill!"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/queen-bargnot-fleemortals.webp"
```
^statblock
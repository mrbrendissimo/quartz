---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/leader
- ttrpg-cli/monster/type/humanoid/orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- Dohma Raskovar
---
# [Dohma Raskovar](3-Mechanics\CLI\bestiary\humanoid/dohma-raskovar-fleemortals.md)
*Source: Flee, Mortals! p. 213*  

```statblock
"name": "Dohma Raskovar (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Leader"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt-xphb.md)"
"hp": !!int "93"
"hit_dice": "11d8 + 44"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "18"
  - !!int "16"
  - !!int "15"
  - !!int "16"
"speed": "35 ft."
"saves":
  - "strength": !!int "6"
  - "constitution": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Orc"
"cr": "5"
"traits":
  - "desc": "If Raskovar fails a saving throw, he can expend a use of his Dohma Rally\
      \ without gaining its benefits (no action required) and succeed instead."
    "name": "Adrenaline Rush"
  - "desc": "When Raskovar isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ and he is reduced to 0 hit points but not killed outright, he can make an\
      \ attack against an enemy (no action required) before the hit point reduction\
      \ is resolved. If the attack hits and its damage reduces the target to 0 hit\
      \ points, Raskovar drops to 1 hit point instead of 0 hit points."
    "name": "Relentless (1/Turn)"
"actions":
  - "desc": "Raskovar makes three Repeating Crossbow attacks or two War Mace attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (2d4\
      \ + 3) bludgeoning damage, and the target is [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the end of their next turn."
    "name": "War Mace"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
      \ 7 (1d12 + 1) piercing damage, and the target's speed is reduced by 10 feet\
      \ until the end of their next turn."
    "name": "Repeating Crossbow"
  - "desc": "Raskovar takes the Dodge action, and ten orc blitzers appear in unoccupied\
      \ spaces within 30 feet of him."
    "name": "Reinforcements (1/Day)"
"bonus_actions":
  - "desc": "Raskovar regains 20 hit points, and he gains resistance to bludgeoning,\
      \ piercing, and slashing damage until the end of his next turn."
    "name": "Dohma Rally (3/Day)"
"reactions":
  - "desc": "When a creature Raskovar can see within 30 feet of him fails an ability\
      \ check or misses with an attack roll, that creature can reroll the check or\
      \ attack, choosing either result."
    "name": "On the House"
"legendary_actions":
  - "desc": "Raskovar has three villain actions. He can take each action once during\
      \ an encounter after an enemy's turn. He can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Each ally within 60 feet of Raskovar who can hear him can move up to\
      \ their speed. After this movement, each enemy within 5 feet of at least one\
      \ creature who moved must make a DC 15 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of Raskovar for 1 minute (save ends at end of turn)."
    "name": "Action 1: Close In"
  - "desc": "Each ally within 60 feet of Raskovar who can hear him can make a Strength\
      \ ([Athletics](/3-Mechanics/CLI/skills.md#Athletics)) check with advantage to\
      \ grapple an enemy within their reach (no action required). Then Raskovar can\
      \ move up to his speed."
    "name": "Action 2: Lockdown"
  - "desc": "Raskovar moves up to his speed without provoking opportunity attacks.\
      \ At the end of the movement, he can make up to five War Mace attacks with advantage."
    "name": "Action 3: Do It Myself"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/dohma-raskovar-fleemortals.png"
```
^statblock
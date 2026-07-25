---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblin
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Goblin Underboss Slime Servant
---
# [Goblin Underboss Slime Servant](3-Mechanics\CLI\bestiary\humanoid/goblin-underboss-slime-servant-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 134*  

If a creature spends 1 continuous minute under the effect of the slime from an olothec's Devolving Tentacle attack, that effect ends and their flesh devolves into a translucent primordial state. The creature loses their memories and sense of self, becoming a slime servant NPC who is loyal to the olothec.

```statblock
"name": "Goblin Underboss Slime Servant (WhereEvilLives)"
"size": "Small"
"type": "humanoid"
"subtype": "goblin, Support"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md),\
  \ [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "13"
  - !!int "12"
  - !!int "12"
  - !!int "10"
"speed": "30 ft., climb 20 ft., swim 30 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+3"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Goblin"
"cr": "2"
"traits":
  - "desc": "The underboss can breathe air and water."
    "name": "Amphibious"
  - "desc": "The underboss doesn't provoke opportunity attacks when they move out\
      \ of an enemy's reach."
    "name": "Crafty"
  - "desc": "Ithu'rath can sense anything the underboss senses, and Ithu'rath can\
      \ speak through their body."
    "name": "Servant Senses"
"actions":
  - "desc": "The underboss makes two Shortsword attacks or two Shortbow attacks. They\
      \ can replace one attack with a use of Command."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
      \ + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. Hit:\
      \ 6 (1d6 + 3) piercing damage."
    "name": "Shortbow"
  - "desc": "The underboss chooses one ally they can see within 30 feet of them. If\
      \ the target can hear the underboss, the target can use their reaction to move\
      \ up to their speed or make one weapon attack."
    "name": "Command"
"bonus_actions":
  - "desc": "Each willing ally within 30 feet of the underboss who can hear them becomes\
      \ reckless until the start of the underboss's next turn. While reckless, a creature\
      \ has advantage on attack rolls, and attack rolls against the creature have\
      \ advantage."
    "name": "Get Reckless (Recharge 6)"
"reactions":
  - "desc": "When a creature the underboss can see hits them with an attack, the underboss\
      \ chooses a willing ally within 5 feet of them. The attack hits the ally instead."
    "name": "Cowardly Commander"
"source":
  - "WhereEvilLives"
```
^statblock
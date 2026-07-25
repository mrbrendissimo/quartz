---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/dragonborn
statblock: inline
statblock-link: "#^statblock"
aliases:
- Scarlet Shadow
---
# [Scarlet Shadow](3-Mechanics\CLI\bestiary\npc/scarlet-shadow-fleemortals.md)
*Source: Flee, Mortals! p. 384*  

```statblock
"name": "Scarlet Shadow (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "dragonborn, Ambusher"
"alignment": "Neutral Evil"
"ac": !!int "19"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"modifier": !!int "7"
"stats":
  - !!int "14"
  - !!int "24"
  - !!int "14"
  - !!int "13"
  - !!int "20"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "10"
  - "intelligence": !!int "4"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Sleight of Hand](/3-Mechanics/CLI/skills.md#Sleight%20of%20Hand)"
    "desc": "+10"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+13"
"damage_resistances": "necrotic"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "Common, Draconic"
"cr": "6"
"traits":
  - "desc": "During his first turn, Scarlet has advantage on attack rolls against\
      \ any creature who hasn't taken a turn.\n\nThe first hit Scarlet scores against\
      \ a surprised creature is a critical hit."
    "name": "Assassinate"
  - "desc": "Scarlet deals an extra 14 (4d6) damage when he hits a target with a weapon\
      \ attack and has advantage on the attack roll, or when the target is within\
      \ 5 feet of an ally of Scarlet who isn't incapacitated and Scarlet doesn't have\
      \ disadvantage on the attack roll."
    "name": "Sneak Attack (1/Turn)"
"actions":
  - "desc": "Scarlet makes three Shadow Blade or three Shortbow attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 14\
      \ (2d6 + 7) necrotic damage. If a target is hit by two or more Shadow Blade\
      \ attacks on a turn, they must succeed on a DC 18 Wisdom saving throw or be\
      \ [blinded](/3-Mechanics/CLI/conditions.md#Blinded) until the end of their next\
      \ turn."
    "name": "Shadow Blade"
  - "desc": "Ranged Weapon Attack: +10 to hit, range 150/600 ft., one target. Hit:\
      \ 11 (1d8 + 7) piercing damage."
    "name": "Longbow"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 11\
      \ (1d8 + 7) slashing damage. If the target is a Medium or smaller creature,\
      \ they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 17).\
      \ Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ they take 22 (5d8) slashing damage at the start of each of their turns, and\
      \ Scarlet can't attack another target."
    "name": "Razor Garrote"
  - "desc": "Scarlet exhales dark flame in a 30-foot cone. Each creature in that area\
      \ must make a DC 18 Dexterity saving throw. On a failed save, a creature takes\
      \ 28 (8d6) necrotic damage and is [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of Scarlet for 1 minute (save ends at end of turn). On a successful save,\
      \ a creature takes half as much damage and isn't [frightened](/3-Mechanics/CLI/conditions.md#Frightened)."
    "name": "Umbral Breath (Recharge 6)"
"bonus_actions":
  - "desc": "Scarlet takes the Dash, Disengage, or Hide action."
    "name": "Cunning Action"
"source":
  - "FleeMortals"
```
^statblock
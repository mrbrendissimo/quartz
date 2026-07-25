---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/hobgoblin
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hobgoblin Smokebinder
---
# [Hobgoblin Smokebinder](3-Mechanics\CLI\bestiary\humanoid/hobgoblin-smokebinder-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 79, Flee, Mortals! p. 151*  

```statblock
"name": "Hobgoblin Smokebinder (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Ambusher"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md),\
  \ [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "17"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "10"
"speed": "30 ft. (fly 30 ft. in smoke form)"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "fire; bludgeoning, piercing, slashing from mundane attacks\
  \ in smoke form"
"condition_immunities": "[grappled](/3-Mechanics/CLI/conditions.md#Grappled), [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
  \ in smoke form"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Goblin, Infernal"
"cr": "2"
"traits":
  - "desc": "The smokebinder can move through a space as narrow as 1 inch wide without\
      \ squeezing."
    "name": "Amorphous (Smoke Form Only)"
  - "desc": "When the smokebinder dies, their corpse unleashes a spray of burning\
      \ orange ichor. Each creature within 5 feet of the smokebinder takes 3 fire\
      \ damage."
    "name": "Infernal Ichor"
"actions":
  - "desc": "Melee Spell Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (3d6)\
      \ fire damage. If the smokebinder has advantage on the attack roll, the target\
      \ is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) and can't speak until\
      \ the end of the target's next turn."
    "name": "Toxic Flame"
  - "desc": "Ranged Spell Attack: +5 to hit, range 60 ft., one target. Hit: 9\
      \ (2d8) fire damage. If the smokebinder has advantage on the attack roll, the\
      \ target can't speak until the end of the target's next turn."
    "name": "Choking Bolt"
"bonus_actions":
  - "desc": "The smokebinder transforms from flesh into a magical gray smoke for 1\
      \ minute. Any equipment they are wearing or carrying is also transformed for\
      \ the duration.\n\nWhile in smoke form, the smokebinder gains a flying speed\
      \ equal to their walking speed, resistance to bludgeoning, piercing, and slashing\
      \ damage from mundane attacks, and immunity to the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained) conditions.\n\n\
      The smokebinder can revert to their true form as a bonus action. If the smokebinder\
      \ becomes [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated) or dies,\
      \ they revert to their true form."
    "name": "Smoke Form (1/Day)"
  - "desc": "The smokebinder takes the Hide action."
    "name": "Sneak (Smoke Form Only)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/hobgoblin-smokebinder-fleemortals.png"
```
^statblock
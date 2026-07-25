---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Qazyldrath
---
# [Qazyldrath](3-Mechanics\CLI\bestiary\npc/qazyldrath-fleemortals.md)
*Source: Flee, Mortals! p. 81*  

```statblock
"name": "Qazyldrath (FleeMortals)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "Solo"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "402"
"hit_dice": "23d20 + 161"
"modifier": !!int "1"
"stats":
  - !!int "27"
  - !!int "12"
  - !!int "24"
  - !!int "14"
  - !!int "16"
  - !!int "18"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "constitution": !!int "14"
  - "wisdom": !!int "10"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_immunities": "acid, necrotic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 120 ft., truesight 60 ft., passive Perception 20"
"languages": "Common, Draconic"
"cr": "21"
"traits":
  - "desc": "Qazyldrath can breathe air and water."
    "name": "Amphibious"
  - "desc": "When Qazyldrath fails a saving throw, they can succeed instead. When\
      \ they do, any areas of magical darkness in the lair are dispelled, and they\
      \ can't use Enshroud or Thwart Healing until the end of their next turn."
    "name": "Consume Shadow (3/Day)"
  - "desc": "Acid and necrotic damage dealt by Qazyldrath ignore damage resistance."
    "name": "Shadow Strength"
"actions":
  - "desc": "Qazyldrath makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +15 to hit, reach 15 ft., one target. Hit: 19\
      \ (2d10 + 8) piercing damage plus 9 (2d8) necrotic damage. If the target is\
      \ a light source or is wearing or holding a light source, that light is extinguished."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +15 to hit, reach 10 ft., one target. Hit: 15\
      \ (2d6 + 8) slashing damage, and Qazyldrath can move the target up to 15 feet\
      \ horizontally."
    "name": "Claw"
  - "desc": "Qazyldrath exhales dark energy in a line that is 90 feet long and 20\
      \ feet wide. Each creature in that area must make a DC 22 Dexterity saving throw,\
      \ taking 24 (7d6) acid damage plus 24 (7d6) necrotic damage on a failed save,\
      \ or half as much damage on a successful one.\n\nAdditionally, that area is\
      \ filled with magical darkness for 1 minute. A creature with darkvision can't\
      \ see through this darkness, and no light except a [daylight](/3-Mechanics/CLI/spells/daylight-xphb.md)\
      \ spell or a light-creating spell of 5th level or higher can illuminate it."
    "name": "Vacuous Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "Shadows cling to one creature Qazyldrath can see within 120 feet of them.\
      \ The target must succeed on a DC 19 Dexterity saving throw or be [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ and vulnerable to necrotic damage until the start of Qazyldrath's next turn."
    "name": "Enshroud"
"reactions":
  - "desc": "When a creature within 60 feet of Qazyldrath regains hit points, Qazyldrath\
      \ forces them to make a DC 19 Constitution saving throw. On a failed save, the\
      \ creature regains half the number of hit points instead."
    "name": "Thwart Healing"
"legendary_actions":
  - "desc": "Qazyldrath has three villain actions. They can take each action once\
      \ during an encounter after an enemy's turn. They can take these actions in\
      \ any order but can use only one per round."
    "name": ""
  - "desc": "Qazyldrath spits acid globules at each enemy they can see within 90 feet\
      \ of them. Each target must succeed on a DC 19 Dexterity saving throw or have\
      \ a globule attached to their body. A creature attached to a globule takes 14\
      \ (4d6) acid damage at the start of their turns. A creature can use an action\
      \ to remove a globule from themself or a creature they can reach."
    "name": "Action 1: Burning Globs"
  - "desc": "Qazyldrath becomes semiincorporeal, gaining resistance to bludgeoning,\
      \ piercing, and slashing damage until the end of their next turn. Qazyldrath\
      \ then teleports up to 120 feet to an unoccupied space that they can see."
    "name": "Action 2: Shadow Form"
  - "desc": "Qazyldrath summons sticky black acid centered on a point they can see\
      \ on the ground within 120 feet of them, creating a 5-foot-deep, 20-foot-radius\
      \ pool. The pool is difficult terrain and lasts for 1 minute. An enemy who starts\
      \ their turn in the pool takes 24 (7d6) acid damage and must succeed on a DC\
      \ 19 Strength saving throw or be [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ until the start of their next turn. An enemy who starts their turn flying\
      \ within 30 feet of the pool must succeed on a DC 19 Dexterity saving throw\
      \ or be pulled down by living acid, landing in the nearest unoccupied space\
      \ of their choice within the pool, take 24 (7d6) acid damage, and be [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ until the start of their next turn."
    "name": "Action 3: Sinking Gloom"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/qazyldrath-whereevillives.png"
```
^statblock
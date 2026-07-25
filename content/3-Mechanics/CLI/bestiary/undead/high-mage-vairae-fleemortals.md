---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- High Mage Vairae
---
# [High Mage Vairae](3-Mechanics\CLI\bestiary\undead/high-mage-vairae-fleemortals.md)
*Source: Flee, Mortals! p. 260*  

```statblock
"name": "High Mage Vairae (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Solo"
"alignment": "Neutral Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "315"
"hit_dice": "42d8 + 126"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "19"
  - !!int "16"
  - !!int "23"
  - !!int "20"
  - !!int "20"
"speed": "30 ft., fly 50 ft. (hover)"
"saves":
  - "constitution": !!int "11"
  - "intelligence": !!int "14"
  - "wisdom": !!int "13"
  - "charisma": !!int "13"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+14"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+13"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+14"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+13"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+13"
"damage_resistances": "fire; cold; bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "truesight 120 ft., passive Perception 23"
"languages": "Abyssal, Common, Draconic, Elvish, Infernal, Sylvan, telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "If Vairae fails a saving throw, they can choose to succeed instead. When\
      \ they do, Vairae has disadvantage on spell attacks until the end of their next\
      \ turn."
    "name": "Draining Resistance (3/Day)"
  - "desc": "Vairae has the Rejuvenation trait found in the lich stat block."
    "name": "Rejuvenation"
  - "desc": "Vairae has advantage on saving throws against powers, spells, and other\
      \ supernatural effects."
    "name": "Supernatural Resistance"
  - "desc": "Vairae is immune to effects that turn Undead."
    "name": "Turn Immunity"
"actions":
  - "desc": "Vairae uses Glare of Undeath and makes four attacks using Conflagration,\
      \ Immortal Pain, Magic Drain, or a combination of them."
    "name": "Multiattack"
  - "desc": "Ranged Spell Attack: +14 to hit, range 150 ft., one target. Hit:\
      \ 35 (10d6) fire damage, and if the target takes both an action and a bonus\
      \ action on their next turn, they take an extra 17 (5d6) fire damage at the\
      \ end of that turn."
    "name": "Conflagration (4th-Level Spell)"
  - "desc": "Melee  or Ranged Spell Attack: +14 to hit, reach 5 ft. or range 90\
      \ ft., one creature. Hit: 28 (8d6) psychic damage, and the target is afflicted\
      \ with pain. While afflicted in this way, the creature's attacks deal half damage.\
      \ After each attack the afflicted creature makes against an enemy, the afflicted\
      \ creature can make a DC 22 Constitution saving throw, ending the effect on\
      \ a success. A cure ailment power, a [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md)\
      \ spell, or a similar supernatural effect also ends the effect."
    "name": "Immortal Pain (4th-Level Spell)"
  - "desc": "Melee  or Ranged Spell Attack: +14 to hit, reach 5 ft. or range 60\
      \ ft., one creature. Hit: 26 (4d12) necrotic damage. If the target is currently\
      \ affected by any spells not cast by Vairae, the target must succeed on a DC\
      \ 22 Wisdom saving throw or those effects end for the target."
    "name": "Magic Drain (4th-Level Spell)"
  - "desc": "Vairae glares at one creature they can see within 60 feet of them. The\
      \ target must succeed on a DC 22 Wisdom saving throw or be compelled to hug\
      \ themself tightly as protection against an unbearably cruel world. A creature\
      \ hugging themself in this way is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ for 1 minute (save ends at end of turn). A creature the target can hear and\
      \ understand can use an action to make a DC 22 Charisma ([Persuasion](/3-Mechanics/CLI/skills.md#Persuasion))\
      \ check, ending the effect on a success."
    "name": "Glare of Undeath"
  - "desc": "Each enemy within 30 feet of a point Vairae can see within 150 feet of\
      \ them must make a DC 22 Strength saving throw. On a failed save, a target's\
      \ innards fly from their body and they take 54 (12d8) piercing damage, fall\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone), and can't stand up until they\
      \ recieve supernatural healing."
    "name": "Machinations of Bone (2/Day)"
"bonus_actions":
  - "desc": "Vairae enters a shadow form and can move up to their speed. While in\
      \ this form, Vairae is immune to bludgeoning, piercing, and slashing damage\
      \ and the [grappled](/3-Mechanics/CLI/conditions.md#Grappled) and [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ conditions, and they can move through a space as narrow as 1 inch without\
      \ squeezing. Vairae reverts to their true form at the end of their turn."
    "name": "Necrotic Form (3rd-Level Spell)"
"reactions":
  - "desc": "When a creature Vairae can see within 120 feet of them targets Vairae\
      \ with an attack, Vairae utters a word of arcane power. The creature must succeed\
      \ on a DC 22 Charisma saving throw or be teleported up to 60 feet to an unoccupied\
      \ space Vairae can see, and if Vairae is no longer a valid target for the triggering\
      \ attack, the attacker must choose a new target or the attack misses."
    "name": "Baleful Teleport (6th-Level Spell)"
"legendary_actions":
  - "desc": "Vairae has three villain actions. They can take each action once during\
      \ an encounter after an enemy's turn. They can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "A cage of black energy springs forth around each enemy within 60 feet\
      \ of Vairae. Each target must make a DC 22 Dexterity saving throw. On a failed\
      \ save, a target takes 27 (5d10) necrotic damage and is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ in the cage for 1 minute or until Vairae is destroyed (save ends at end of\
      \ turn). On a successful save, a target takes half as much damage and isn't\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained). If a [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ creature teleports out of their cage, the effect ends for them."
    "name": "Action 1: Cages of Wasting"
  - "desc": "Vairae unleashes a wave of canceling magic. Each creature within 60 feet\
      \ of Vairae must make a DC 22 Wisdom saving throw. On a failed save, a target\
      \ can't benefit from magic items or cast spells of 4th level or higher until\
      \ the end of Vairae's next turn."
    "name": "Action 2: My Magic Alone"
  - "desc": "Vairae fires black bolts of magic from their body. Each creature within\
      \ 60 feet of them must make a DC 22 Dexterity saving throw, taking 78 (12d12)\
      \ necrotic damage on a failed save, or half as much damage on a successful one.\
      \ The spirit of a Humanoid killed by this damage rises at the start of Vairae's\
      \ next turn as a wraith who permanently follows Vairae's verbal commands."
    "name": "Action 3: Necrostorm"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/undead/token/high-mage-vairae-fleemortals.png"
```
^statblock
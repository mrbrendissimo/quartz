---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
- ttrpg-cli/monster/type/fiend/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Devil Magistrate
---
# [Devil Magistrate](3-Mechanics\CLI\bestiary\fiend/devil-magistrate-fleemortals.md)
*Source: Flee, Mortals! p. 69*  

```statblock
"name": "Devil Magistrate (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "devil, Skirmisher"
"alignment": "typically  Lawful Evil"
"ac": !!int "18"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "182"
"hit_dice": "28d8 + 56"
"modifier": !!int "6"
"stats":
  - !!int "12"
  - !!int "22"
  - !!int "14"
  - !!int "11"
  - !!int "16"
  - !!int "19"
"speed": "50 ft."
"saves":
  - "dexterity": !!int "10"
  - "wisdom": !!int "7"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+10"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+10"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "fire"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Common, Infernal"
"cr": "12"
"traits":
  - "desc": "If a creature the magistrate can hear within 60 feet of them speaks the\
      \ magistrate's true name aloud, the magistrate loses their damage resistances,\
      \ damage immunities, and Devilish Charm reaction for 24 hours."
    "name": "True Name"
"actions":
  - "desc": "The magistrate makes two Infernal Knife attacks and one Obsidian Kris\
      \ attack."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Weapon Attack: +10 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 15 (2d8 + 6) piercing damage plus 9 (2d8) fire damage,\
      \ and the target is [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of their allies until the end of their next turn."
    "name": "Infernal Knife"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 15\
      \ (2d8 + 6) piercing damage, and if the target is [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
      \ they can't take reactions until the [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ condition ends for them."
    "name": "Obsidian Kris"
"reactions":
  - "desc": "When the magistrate is targeted by an attack, power, spell, or other\
      \ supernatural effect by a creature they can see within 60 feet of them, the\
      \ creature must make a DC 16 Charisma saving throw. On a failed save, the creature\
      \ is [charmed](/3-Mechanics/CLI/conditions.md#Charmed) by the magistrate until\
      \ the start of the creature's next turn, and the magistrate chooses a new target\
      \ the magistrate can see for the triggering effect. The new target must be within\
      \ the triggering effect's range."
    "name": "Devilish Charm (2/Day)"
"source":
  - "FleeMortals"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental/earth
- ttrpg-cli/monster/type/elemental/fire
- ttrpg-cli/monster/type/elemental/retainer
- ttrpg-cli/monster/type/elemental/water
statblock: inline
statblock-link: "#^statblock"
aliases:
- Blood Seneschal
---
# [Blood Seneschal](3-Mechanics\CLI\bestiary\elemental/blood-seneschal-fleemortals.md)
*Source: Flee, Mortals! p. 102*  

```statblock
"name": "Blood Seneschal (FleeMortals)"
"size": "Medium"
"type": "elemental"
"subtype": "earth, fire, water, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "10"
  - !!int "12"
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
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+0 plus PB"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+1 plus PB"
"damage_resistances": "fire, necrotic"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Dwarvish, Elvish, Giant, Primordial"
"actions":
  - "desc": "Melee  or Ranged Spell Attack: +3 plus PB to hit, reach 5 ft. or range\
      \ 60 ft., one target. Hit: 1d4 plus PB necrotic damage, and the target is\
      \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until the end of the seneschal's\
      \ next turn. Beginning at 7th level, the seneschal can make this attack twice,\
      \ instead of once, when they take the Attack action on their turn."
    "name": "Signature Attack (Blood Curse)"
  - "desc": "As an action, the seneschal empowers the blood of up to PB creatures\
      \ within 30 feet of them. Each target can expend 1 Hit Die, rolling it and regaining\
      \ hit points equal to twice the result plus their Constitution modifier."
    "name": "3rd Level: Coagulate (3/Day)"
  - "desc": "As an action, the seneschal chooses a creature they can see within 60\
      \ feet of them. The target must succeed on a DC 10 plus PB Wisdom saving throw\
      \ or move up to their speed in a direction of the seneschal's choice. During\
      \ this movement, the seneschal can force them to make one attack against a creature\
      \ of the seneschal's choice (no action required)."
    "name": "5th Level: Blood Puppet (3/Day)"
  - "desc": "As an action, the seneschal arrests the hearts of up to PB creatures\
      \ within 30 feet of them. Each target must make a DC 10 plus PB Constitution\
      \ saving throw. On a failed save, a creature takes PBd6 necrotic damage and\
      \ is [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed) for 1 minute (save\
      \ ends at end of turn). On a successful save, a creature takes half as much\
      \ damage and isn't [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)."
    "name": "7th Level: Blood Bondage (1/Day)"
"source":
  - "FleeMortals"
```
^statblock
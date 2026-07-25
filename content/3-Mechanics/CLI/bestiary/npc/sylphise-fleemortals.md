---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sylphise
---
# [Sylphise](3-Mechanics\CLI\bestiary\npc/sylphise-fleemortals.md)
*Source: Flee, Mortals! p. 370*  

```statblock
"name": "Sylphise (FleeMortals)"
"size": "Medium"
"type": "fey"
"subtype": "Skirmisher"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "77"
"hit_dice": "14d8 + 14"
"modifier": !!int "5"
"stats":
  - !!int "8"
  - !!int "20"
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "22"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "7"
  - "wisdom": !!int "3"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Elvish, Sylvan, telepathy 60 ft."
"cr": "4"
"traits":
  - "desc": "When a creature who can see Sylphise targets her with an attack, power,\
      \ or spell, the creature must succeed on a DC 16 Wisdom saving throw or be [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ until the start of their next turn (no action required)."
    "name": "Fey Countenance (1/Turn)"
  - "desc": "Sylphise can communicate with Beasts and Plants as if they shared a language."
    "name": "Speak with Beasts and Plants"
  - "desc": "Sylphise has advantage on saving throws against powers, spells, and other\
      \ supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "Sylphise makes three Claw attacks or uses Sibilant Whispers twice."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d6\
      \ + 5) slashing damage plus 3 (d6) psychic damage."
    "name": "Claw"
  - "desc": "One creature Sylphise can see within 60 feet of her must succeed on a\
      \ DC 16 Charisma saving throw or take 10 (3d6) psychic damage."
    "name": "Sibilant Whispers"
  - "desc": "Sylphise magically enters the Ethereal Plane from the Mundane World,\
      \ or vice versa."
    "name": "Etherealness"
"reactions":
  - "desc": "If a creature misses Sylphise with an attack, she can move up to her\
      \ speed without provoking opportunity attacks from that creature."
    "name": "Too Slow!"
"source":
  - "FleeMortals"
```
^statblock
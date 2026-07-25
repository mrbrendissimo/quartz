---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/retainer
- ttrpg-cli/monster/type/undead/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ghost Sycophant
---
# [Ghost Sycophant](3-Mechanics\CLI\bestiary\undead/ghost-sycophant-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 128, Flee, Mortals! p. 250*  

```statblock
"name": "Ghost Sycophant (WhereEvilLives)"
"size": "Medium"
"type": "undead"
"subtype": "undead, Retainer"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "light armor"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "16"
"speed": "30 ft., fly 30 ft. (hover)"
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
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3 plus PB"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+1 plus PB"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"damage_immunities": "necrotic"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, any two languages they knew in life"
"actions":
  - "desc": "Melee  or Ranged Spell Attack: +3 plus PB to hit, reach 5 ft. or range\
      \ 60 ft., one target. Hit: 5 (d10) necrotic damage. This spell's damage increases\
      \ by d10 when the sycophant reaches 5th level (2d10), 11th level (3d10), and\
      \ 17th level (4d10)."
    "name": "Signature Attack (Dark Essence)"
  - "desc": "When the sycophant hits a creature with a signature attack, the target\
      \ must also succeed on a DC 10 plus PB Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the sycophant for 1 minute (save ends at end of turn)."
    "name": "3rd Level: Call of the Dead (3/Day)"
  - "desc": "As an action, the sycophant becomes [invisible](/3-Mechanics/CLI/conditions.md#Invisible)\
      \ for 1 minute or until they use a bonus action to end this effect. While [invisible](/3-Mechanics/CLI/conditions.md#Invisible),\
      \ the sycophant can move through creatures and objects as if they were difficult\
      \ terrain, and the sycophant's signature attacks deal an extra PB damage to\
      \ creatures who can't see them. The sycophant takes 5 (d10) force damage if\
      \ they end their turn inside an object."
    "name": "5th Level: Astral Presence (3/Day)"
  - "desc": "As an action, the sycophant chooses up to PB creatures they can see within\
      \ 30 feet of them. Each target must succeed on a DC 10 plus PB Charisma saving\
      \ throw or make an attack against their nearest ally (no action required). A\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened) creature has disadvantage\
      \ on the saving throw."
    "name": "7th Level: Whispers of the Dead (3/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
```
^statblock
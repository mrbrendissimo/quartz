---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- Terracotta Warrior
---
# [Terracotta Warrior](3-Mechanics\CLI\bestiary\construct/terracotta-warrior-toa.md)
*Source: Tomb of Annihilation p. 161*  

```statblock
"name": "Terracotta Warrior (ToA)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "11"
  - !!int "13"
  - !!int "1"
  - !!int "3"
  - !!int "1"
"speed": "25 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "1"
"traits":
  - "desc": "If a critical hit is scored against the terracotta warrior, it shatters\
      \ and is destroyed."
    "name": "Fragile"
  - "desc": "The terracotta warrior is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ while in the area of an [antimagic field](/3-Mechanics/CLI/spells/antimagic-field-xphb.md).\
      \ If targeted by [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ the terracotta warrior must succeed on a Constitution saving throw against\
      \ the caster's spell save DC or fall [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)\
      \ for 1 minute."
    "name": "Antimagic Susceptibility"
  - "desc": "While the terracotta warrior remains motionless, it is indistinguishable\
      \ from a terracotta statue."
    "name": "False Appearance"
"actions":
  - "desc": "The terracotta warrior makes two melee attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
"source":
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/construct/token/terracotta-warrior-toa.webp"
```
^statblock
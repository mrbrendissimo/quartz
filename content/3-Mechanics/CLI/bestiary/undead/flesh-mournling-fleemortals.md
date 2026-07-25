---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Flesh Mournling
---
# [Flesh Mournling](3-Mechanics\CLI\bestiary\undead/flesh-mournling-fleemortals.md)
*Source: Flee, Mortals! p. 263*  

```statblock
"name": "Flesh Mournling (FleeMortals)"
"size": "Large"
"type": "undead"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "18"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "understands the languages of their creator but can't speak"
"cr": "5"
"traits":
  - "desc": "When an enemy who can hear the mournling starts their turn within 30\
      \ feet of the mournling, the enemy must succeed on a DC 15 Wisdom saving throw\
      \ or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened) of the mournling\
      \ until the start of their next turn. A creature who succeeds on their saving\
      \ throw is immune to the Horrid Sob of all flesh mournlings for 24 hours."
    "name": "Horrid Sob"
  - "desc": "The mournling is immune to any power, spell, or effect that would alter\
      \ their form."
    "name": "Immutable Form"
"actions":
  - "desc": "The mournling makes two Slam attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 14\
      \ (3d6 + 4) bludgeoning damage. If the target is [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the mournling, the target falls [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Slam"
  - "desc": "The flesh mournling screams with unbearable pain in a 30-foot cone. Each\
      \ creature in that area who can hear the mournling must make a DC 15 Constitution\
      \ saving throw. On a failed save, a creature's eyes water uncontrollably, they\
      \ take 16 (3d10) psychic damage, and they can't see anything more than 5 feet\
      \ away until the end of their next turn. On a successful save, a creature takes\
      \ half as much damage and suffers no other effect."
    "name": "Agonizing Wail (Recharge 5-6)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/undead/token/flesh-mournling-fleemortals.png"
```
^statblock
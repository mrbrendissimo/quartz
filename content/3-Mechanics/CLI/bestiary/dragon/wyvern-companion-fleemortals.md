---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wyvern Companion
---
# [Wyvern Companion](3-Mechanics\CLI\bestiary\dragon/wyvern-companion-fleemortals.md)
*Source: Flee, Mortals! p. 290*  

```statblock
"name": "Wyvern Companion (FleeMortals)"
"size": "Large"
"type": "dragon"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "5"
  - !!int "14"
  - !!int "6"
"speed": "25 ft. (see learning to fly)"
"saves":
  - "name": "Strength"
    "desc": "+3 plus PB"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2 plus PB"
"damage_immunities": "acid"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"traits":
  - "desc": "The wyvern has a flying speed of 10 × PB feet."
    "name": "Learning to Fly"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Stinger)"
  - "desc": "The wyvern makes a signature attack with a reach of 15 feet. On a hit,\
      \ the attack deals an extra PB acid damage."
    "name": "1st Level: Acidic Sting (2 Ferocity)"
  - "desc": "The wyvern pounces on a Large or smaller creature within 5 feet of them,\
      \ attempting to melt their prey's flesh with acid and drink it. The target must\
      \ succeed on a DC 10 plus PB Dexterity saving throw or fall [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and take 1d4 plus PB acid damage. The wyvern gains temporary hit points equal\
      \ to the acid damage dealt."
    "name": "3rd Level: Liquefied Meal (5 Ferocity)"
  - "desc": "The wyvern sweeps their tail in a 15-foot cone. Each creature in that\
      \ area must make a DC 10 plus PB Strength saving throw or take PBd6 bludgeoning\
      \ damage and be pushed up to 10 feet away from the wyvern."
    "name": "5th Level: Tail Sweep (8 Ferocity)"
"reactions":
  - "desc": "When a creature the wyvern can see within 30 feet of them reduces the\
      \ wyvern's caregiver to 0 hit points or scores a critical hit against the caregiver,\
      \ the wyvern can move up to their speed. If the wyvern ends this movement within\
      \ 5 feet of the attacker, the wyvern can make a signature attack against them."
    "name": "Enraged Protector"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/dragon/token/wyvern-companion-fleemortals.png"
```
^statblock
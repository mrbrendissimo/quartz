---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Manticore Companion
---
# [Manticore Companion](3-Mechanics\CLI\bestiary\monstrosity/manticore-companion-fleemortals.md)
*Source: Flee, Mortals! p. 187*  

```statblock
"name": "Manticore Companion (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "6"
  - !!int "12"
  - !!int "8"
"speed": "30 ft. (see learning to fly)"
"saves":
  - "name": "Dexterity"
    "desc": "+1 plus PB"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1 plus PB"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+1 plus PB"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"traits":
  - "desc": "The manticore has a flying speed of 10 × PB feet."
    "name": "Learning to Fly"
  - "desc": "The manticore can mimic any words or phrases they have heard in a language\
      \ the manticore's caregiver understands. A creature who hears the speech can\
      \ tell it is an imitation with a successful DC 10 plus PB Wisdom ([Insight](/3-Mechanics/CLI/skills.md#Insight))\
      \ check."
    "name": "Mimicry"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Bite)"
  - "desc": "The manticore hurls a spine from its tail. This attack uses the statistics\
      \ for their signature attack, except the spine is a ranged weapon with a normal\
      \ range of 30 feet and a long range of 60 feet, and on a hit, the attack deals\
      \ an extra PB of poison damage."
    "name": "1st Level: Tail Spike (2 Ferocity)"
  - "desc": "Each enemy within 30 feet of the manticore who can hear them must succeed\
      \ on a DC 10 plus PB Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of them until the end of the manticore's next turn."
    "name": "3rd Level: Trumpeting Howl (5 Ferocity)"
  - "desc": "The manticore stings a target within 10 feet of them with their tail.\
      \ The target must make a DC 10 plus PB Constitution saving throw. On a failed\
      \ save, the target takes PBd10 poison damage and becomes [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the end of their next turn. On a successful save, the target takes half\
      \ as much damage and isn't [dazed](/3-Mechanics/CLI/conditions.md#Dazed)."
    "name": "5th Level: Poisoned Sting (8 Ferocity)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/manticore-companion-fleemortals.png"
```
^statblock
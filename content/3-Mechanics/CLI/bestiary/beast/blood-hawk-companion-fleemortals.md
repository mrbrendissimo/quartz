---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Blood Hawk Companion
---
# [Blood Hawk Companion](3-Mechanics\CLI\bestiary\beast/blood-hawk-companion-fleemortals.md)
*Source: Flee, Mortals! p. 45*  

```statblock
"name": "Blood Hawk Companion (FleeMortals)"
"size": "Small"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "12"
  - !!int "5"
  - !!int "14"
  - !!int "10"
"speed": "10 ft., fly 60 ft."
"saves":
  - "name": "Dexterity"
    "desc": "+3 plus PB"
  - "name": "Wisdom"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2 plus PB"
"senses": "passive Perception 0"
"languages": ""
"traits":
  - "desc": "The hawk has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Keen Sight"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Beak)"
  - "desc": "The hawk makes a signature attack. On a hit, the next attack made against\
      \ the target before the start of the hawk's next turn has advantage."
    "name": "1st Level: Distracting Attack (2 Ferocity)"
  - "desc": "The hawk moves up to their speed without provoking opportunity attacks.\
      \ During or after this move, they can make a signature attack against one target.\
      \ On a hit, the target must succeed on a DC 10 plus PB Strength saving throw\
      \ or drop one item they are holding."
    "name": "3rd Level: Swooping Attack (5 Ferocity)"
  - "desc": "The hawk moves up to their speed without provoking opportunity attacks,\
      \ then they can dive onto one creature within 5 feet of them. The target must\
      \ make a DC 10 plus PB Dexterity saving throw. On a failed save, the target\
      \ takes PBd10 slashing damage and is [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ until the end of the hawk's next turn. On a successful save, the target takes\
      \ half as much damage and isn't [blinded](/3-Mechanics/CLI/conditions.md#Blinded)."
    "name": "5th Level: Storm of Talons (8 Ferocity)"
"reactions":
  - "desc": "When the hawk's caregiver is hit with an attack while the hawk is within\
      \ 30 feet of them, the hawk moves up to their speed without provoking opportunity\
      \ attacks. If the hawk ends this movement within 5 feet of the caregiver, the\
      \ hawk becomes the target of the triggering attack instead, and the attack deals\
      \ half as much damage."
    "name": "Swoop In (Recharges after a Long Rest)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/blood-hawk-companion-fleemortals.png"
```
^statblock
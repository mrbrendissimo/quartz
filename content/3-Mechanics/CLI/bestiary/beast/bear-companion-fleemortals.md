---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bear Companion
---
# [Bear Companion](3-Mechanics\CLI\bestiary\beast/bear-companion-fleemortals.md)
*Source: Flee, Mortals! p. 44*  

```statblock
"name": "Bear Companion (FleeMortals)"
"size": "Large"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "10 plus PB (natural armor)"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "10"
  - !!int "15"
  - !!int "8"
  - !!int "12"
  - !!int "7"
"speed": "40 ft., swim 30 ft."
"saves":
  - "name": "Strength"
    "desc": "+3 plus PB"
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1 plus PB"
"senses": "passive Perception 0"
"languages": ""
"traits":
  - "desc": "The bear's proficiency bonus is doubled for Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on smell, and they can smell creatures even through dirt,\
      \ snow, and water."
    "name": "Exceptional Smell"
  - "desc": "The bear has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ and Wisdom ([Survival](/3-Mechanics/CLI/skills.md#Survival)) checks made in\
      \ their native terrain (as determined by you and the GM)."
    "name": "Familiar Territory"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage (Bite) or slashing damage (Claw)."
    "name": "Signature Attack (Bite or Claw)"
  - "desc": "The bear makes a signature attack. On a hit, the attack deals an extra\
      \ PB damage. On a miss, the bear deals PB slashing damage to the target and\
      \ gains 2 ferocity."
    "name": "1st Level: Tenacious Strike (2 Ferocity)"
  - "desc": "The bear makes a signature attack. On a hit, the target is also [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 10 plus PB). While [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ in this way, the bear's attacks (including the triggering attack) deal an\
      \ extra PB damage, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ if they are Large or smaller, and the bear can't make a signature attack against\
      \ another target."
    "name": "3rd Level: Pummel (5 Ferocity)"
  - "desc": "The bear makes a signature Claw attack against PB creatures of their\
      \ choice within 5 feet of them. At the end of their turn, the bear gains 1 ferocity\
      \ for every attack that missed."
    "name": "5th Level: Clawing Frenzy (8 Ferocity)"
"bonus_actions":
  - "desc": "The bear detects the location of each living creature within 10 × PB\
      \ feet of them, unless the creature is hiding their scent by supernatural means."
    "name": "Hunt by Scent"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/bear-fleemortals.png"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/dragon/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Dragonet
---
# [Dragonet](3-Mechanics\CLI\bestiary\dragon/dragonet-fleemortals.md)
*Source: Flee, Mortals! p. 73*  

```statblock
"name": "Dragonet (FleeMortals)"
"size": "Tiny"
"type": "dragon"
"subtype": "Support"
"alignment": "typically  Neutral Good"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "14"
"hit_dice": "4d4 + 4"
"modifier": !!int "3"
"stats":
  - !!int "5"
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "12"
  - !!int "13"
"speed": "10 ft., fly 30 ft., swim 20 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Draconic"
"cr": "1/4"
"traits":
  - "desc": "The dragonet has advantage on Intelligence ([Arcana](/3-Mechanics/CLI/skills.md#Arcana))\
      \ checks made to reveal information about supernatural effects and objects they\
      \ can see. Additionally, they always know if their emotions are being sensed,\
      \ their thoughts are being read, or they are being targeted or perceived by\
      \ any divination spells."
    "name": "Arcane Acumen"
  - "desc": "When a creature speaks in Draconic, the dragonet has advantage on Wisdom\
      \ ([Insight](/3-Mechanics/CLI/skills.md#Insight)) checks to determine whether\
      \ they are lying."
    "name": "True Words"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
      \ + 3) slashing damage."
    "name": "Claw"
  - "desc": "The dragonet exhales sparkling light in a 15-foot cone. Each object in\
      \ that area is outlined in light for 1 minute, and each creature in that area\
      \ must succeed on a DC 13 Dexterity saving throw or also be outlined in light\
      \ for the duration. Outlined creatures and objects shed dim light in a 5-foot\
      \ radius, and if any outlined creatures or objects bear magic, the dragonet\
      \ can learn its school of magic, if any, by looking at it. Any attack roll against\
      \ an outlined creature or object has advantage if the attacker can see the target,\
      \ and the outlined creature or object can't benefit from being [invisible](/3-Mechanics/CLI/conditions.md#Invisible)."
    "name": "Revealing Breath (Recharges after a Short or Long Rest)"
  - "desc": "For 1 minute, the dragonet gains truesight out to a range of 60 feet."
    "name": "Truesight (Recharges after a Long Rest)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/dragon/token/dragonet-fleemortals.png"
```
^statblock
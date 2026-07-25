---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Minotaur
---
# [Minotaur](3-Mechanics\CLI\bestiary\monstrosity/minotaur-fleemortals.md)
*Source: Flee, Mortals! p. 196*  

```statblock
"name": "Minotaur (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Skirmisher"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "57"
"hit_dice": "6d10 + 24"
"modifier": !!int "3"
"stats":
  - !!int "19"
  - !!int "16"
  - !!int "19"
  - !!int "10"
  - !!int "13"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "If the minotaur moves at least 20 feet straight toward a Large or smaller\
      \ creature and then hits the creature with a Goring Horns attack on the same\
      \ turn, that target must succeed on a DC 14 Constitution saving throw or be\
      \ [dazed](/3-Mechanics/CLI/conditions.md#Dazed) until the start of the minotaur's\
      \ next turn."
    "name": "Dizzying Gore"
  - "desc": "The minotaur always knows which way is north and can't become lost."
    "name": "Minotaur Senses"
"actions":
  - "desc": "The minotaur makes one Maul attack and one Goring Horns attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 13\
      \ (2d8 + 4) bludgeoning damage. If the target is Large or smaller, the minotaur\
      \ can push the target 5 feet away."
    "name": "Maul"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
      \ + 4) piercing damage."
    "name": "Goring Horns"
"reactions":
  - "desc": "When a creature the minotaur can see within 40 feet of them deals damage\
      \ to the minotaur, the minotaur can move up to their speed. If the minotaur\
      \ ends this movement within 5 feet of that creature, the minotaur can make a\
      \ Goring Horns attack against them."
    "name": "Retaliatory Gore"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/minotaur-fleemortals.png"
```
^statblock
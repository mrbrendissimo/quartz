---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant/controller
- ttrpg-cli/monster/type/plant/fungus
statblock: inline
statblock-link: "#^statblock"
aliases:
- Deep Dreamer
---
# [Deep Dreamer](3-Mechanics\CLI\bestiary\plant/deep-dreamer-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 242, Flee, Mortals! p. 256*  

```statblock
"name": "Deep Dreamer (WhereEvilLives)"
"size": "Large"
"type": "plant"
"subtype": "fungus, Controller"
"alignment": "typically  Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "21d10 + 63"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "10"
  - !!int "16"
  - !!int "20"
  - !!int "12"
  - !!int "16"
"speed": "0 ft., fly 20 ft. (hover)"
"saves":
  - "intelligence": !!int "10"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+8"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Deep Speech, Undercommon, telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "The dreamer is immune to divination spells and to any effect that would\
      \ sense their emotions or read their thoughts."
    "name": "Psionic Shroud"
"actions":
  - "desc": "The dreamer makes two Tendrils attacks and uses Dream Spores, if available."
    "name": "Multiattack"
  - "desc": "Melee Power Attack: +10 to hit, reach 10 ft., one target. Hit: 12\
      \ (2d6 + 5) slashing damage plus 22 (4d10) psychic damage. If the target is\
      \ [charmed](/3-Mechanics/CLI/conditions.md#Charmed) by the dreamer, the dreamer\
      \ regains hit points equal to half the psychic damage dealt."
    "name": "Tendrils"
  - "desc": "The dreamer releases a cloud of psionic spores. Each creature within\
      \ 60 feet of them must succeed on a DC 18 Intelligence saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by the dreamer for 1 minute.\n\nWhile [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ in this way, a creature must use their movement during their turn to move\
      \ within 10 feet of the dreamer by the safest available route.\n\nA creature\
      \ [charmed](/3-Mechanics/CLI/conditions.md#Charmed) in this way can repeat the\
      \ saving throw whenever they take damage, ending the effect on themself on a\
      \ success."
    "name": "*Dream Spores (5th-Order Power; Recharge 5-6)"
"reactions":
  - "desc": "When a creature makes an attack against the dreamer, the dreamer chooses\
      \ a creature [charmed](/3-Mechanics/CLI/conditions.md#Charmed) by the dreamer\
      \ within the attack's range, and the [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ creature becomes the target of the attack instead."
    "name": "Rouse Dreamer"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/plant/token/deep-dreamer-fleemortals.png"
```
^statblock
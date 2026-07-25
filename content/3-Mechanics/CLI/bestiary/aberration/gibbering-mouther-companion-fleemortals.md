---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gibbering Mouther Companion
---
# [Gibbering Mouther Companion](3-Mechanics\CLI\bestiary\aberration/gibbering-mouther-companion-fleemortals.md)
*Source: Flee, Mortals! p. 115*  

```statblock
"name": "Gibbering Mouther Companion (FleeMortals)"
"size": "Medium"
"type": "aberration"
"subtype": "Companion"
"alignment": "typically  Chaotic Neutral"
"ac_class": "11 plus PB (natural armor)"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "12"
  - !!int "16"
  - !!int "7"
  - !!int "11"
  - !!int "5"
"speed": "20 ft., fly 10 ft. (hover), swim 20 ft."
"saves":
  - "name": "Dexterity"
    "desc": "+1 plus PB"
  - "name": "Constitution"
    "desc": "+3 plus PB"
  - "name": "Wisdom"
    "desc": "+0 plus PB"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"traits":
  - "desc": "The gibbering mouther is immune to any power, spell, or effect that would\
      \ alter their form."
    "name": "Immutable Form"
  - "desc": "The gibbering mouther envelops their surroundings in their shifting reality.\
      \ The area within 10 feet of them is difficult terrain for other creatures."
    "name": "Viscous Vicinity"
"actions":
  - "desc": "Melee Power Attack: +3 plus PB to hit, reach 5 ft., one creature. Hit:\
      \ 1d6 plus PB psychic damage."
    "name": "Signature Attack (Reality Rend)"
  - "desc": "The gibbering mouther makes a signature attack with a reach of 10 feet.\
      \ On a hit, the attack deals an extra PB damage, and the gibbering mouther can\
      \ pull the target 5 feet toward them."
    "name": "1st Level: Stretch Attack (2 Ferocity)"
  - "desc": "The gibbering mouther warps reality around up to PB enemies within 60\
      \ feet of them. Each target must succeed on a DC 10 plus PB Strength saving\
      \ throw or be pulled up to 20 feet directly toward the gibbering mouther."
    "name": "3rd Level: Reality Pull (5 Ferocity)"
  - "desc": "The gibbering mouther and each ally within 30 feet of them gains a +PB\
      \ bonus to damage rolls and has their speed doubled until the start of the gibbering\
      \ mouther's next turn. Additionally, the gibbering mouther can make one signature\
      \ attack as part of this action."
    "name": "5th Level: Vicinity Shift (8 Ferocity)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/gibbering-mouther-companion-fleemortals.png"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/ooze/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gem Jelly Companion
---
# [Gem Jelly Companion](3-Mechanics\CLI\bestiary\ooze/gem-jelly-companion-fleemortals.md)
*Source: Flee, Mortals! p. 343*  

```statblock
"name": "Gem Jelly Companion (FleeMortals)"
"size": "Large"
"type": "ooze"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "11 plus PB (natural armor)"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "16"
  - !!int "5"
  - !!int "10"
  - !!int "8"
"speed": "30 ft., climb 20 ft."
"saves":
  - "name": "Constitution"
    "desc": "+3 plus PB"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "-1 plus PB"
"damage_resistances": "acid"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"traits":
  - "desc": "The jelly can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
  - "desc": "While the jelly remains motionless, they are indistinguishable from a\
      \ natural crystal formation."
    "name": "False Appearance"
  - "desc": "The jelly can occupy their caregiver's space and vice versa, and it doesn't\
      \ count as difficult terrain for them.\n\nWhile occupying the same space as\
      \ the jelly, the caregiver can take the Hide action to hide from creatures outside\
      \ the jelly."
    "name": "Flowing Jelly"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Pseudopod)"
  - "desc": "The jelly makes a signature attack with a reach of 10 feet. On a hit,\
      \ the attack deals an extra PB damage, and the jelly can pull the target 5 feet\
      \ toward them."
    "name": "1st Level: Stretch Attack (2 Ferocity)"
  - "desc": "The jelly grows sharp crystals from the ground in a 20-foot-radius sphere\
      \ centered on the jelly. Until the start of the jelly's next turn, that area\
      \ becomes difficult terrain for their enemies, and when an enemy moves into\
      \ or within that area, the enemy takes 2 × PB piercing damage for every 5 feet\
      \ they travel."
    "name": "3rd Level: Crystallize (5 Ferocity)"
  - "desc": "The jelly ejects jagged crystals from their body toward each enemy within\
      \ 10 feet of them.\n\nEach target must make a DC 10 plus PB Dexterity saving\
      \ throw, taking PBd6 piercing damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "5th Level: Shatter (8 Ferocity)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/ooze/token/gem-jelly-companion-fleemortals.png"
```
^statblock
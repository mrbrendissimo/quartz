---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lightbender Companion
---
# [Lightbender Companion](3-Mechanics\CLI\bestiary\monstrosity/lightbender-companion-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 245, Flee, Mortals! p. 181*  

```statblock
"name": "Lightbender Companion (WhereEvilLives)"
"size": "Large"
"type": "monstrosity"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "6"
  - !!int "12"
  - !!int "8"
"speed": "50 ft."
"saves":
  - "name": "Strength"
    "desc": "+3 plus PB"
  - "name": "Dexterity"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1 plus PB"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+2 plus PB"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Bite)"
  - "desc": "The lightbender makes a signature attack. On a hit, the attack deals\
      \ an extra PB radiant damage to the target, and a different creature the lightbender\
      \ chooses within 15 feet of them takes PB radiant damage."
    "name": "1st Level: Tail Whip (2 Ferocity)"
  - "desc": "The lightbender teleports 30 feet to an unoccupied space they can see.\
      \ Before or after teleporting, the lightbender can make a signature attack.\
      \ If the attack hits, the target is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "3rd Level: Silent Pounce (5 Ferocity)"
  - "desc": "Each creature within 10 feet of the lightbender must succeed on a DC\
      \ 10 plus PB Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by the lightbender until the end of the lightbender's next turn. While [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ in this way, a creature is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ and has a speed of 0. If a creature [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ in this way takes damage or if someone else uses an action to shake the creature\
      \ out of their stupor, the condition ends on that creature."
    "name": "5th Level: Hypnotic Mane (8 Ferocity)"
"reactions":
  - "desc": "When the lightbender and their caregiver are within 30 feet of each other\
      \ and one of them is hit by an attack, the lightbender reveals that both they\
      \ and their caregiver are past visual imprints. The lightbender and the caregiver\
      \ each appear in an unoccupied space they can see within 30 feet of their imprints,\
      \ the attack misses, then the imprints disappear. The lightbender can't use\
      \ this reaction if the attacker relies on senses other than sight, such as blindsight,\
      \ or if they can perceive illusions as false, as with truesight."
    "name": "Shared Afterimage (Recharges after a Long Rest)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/lightbender-companion-fleemortals.webp"
```
^statblock
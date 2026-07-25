---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Basilisk Companion
---
# [Basilisk Companion](3-Mechanics\CLI\bestiary\monstrosity/basilisk-companion-fleemortals.md)
*Source: Flee, Mortals! p. 49*  

```statblock
"name": "Basilisk Companion (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "15 plus PB (natural armor)"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "5"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+1 plus PB"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Bite)"
  - "desc": "The basilisk makes a signature attack. On a hit, the attack deals an\
      \ extra PB damage, and a different creature the basilisk chooses within 5 feet\
      \ of them takes PB poison damage."
    "name": "1st Level: Poison Spittle (2 Ferocity)"
  - "desc": "The basilisk chooses up to three creatures they can see within 15 feet\
      \ of them. Each creature must succeed on a DC 10 plus PB Constitution saving\
      \ throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until the\
      \ start of the basilisk's next turn."
    "name": "3rd Level: Poison Gaze (5 Ferocity)"
  - "desc": "The basilisk targets one creature they can see within 30 feet of them.\
      \ The target must succeed on a DC 10 plus PB Constitution saving throw or be\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained) as they magically\
      \ begin to turn to stone. A creature [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ in this way must repeat the saving throw at the end of their turn. On a successful\
      \ save, the effect ends. On a failed save, the creature is [petrified](/3-Mechanics/CLI/conditions.md#Petrified)\
      \ for 1 hour or until freed by a cure ailment power, [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md)\
      \ spell, or similar supernatural effect."
    "name": "5th Level: Lesser Petrifying Eye Beams (8 Ferocity)"
"reactions":
  - "desc": "When a creature who can see the basilisk is hit by an attack by the basilisk's\
      \ caregiver, the basilisk forces that creature to make a DC 10 plus PB Constitution\
      \ saving throw. On a failed save, the target can't make opportunity attacks\
      \ and has their speed reduced by 10 feet until the start of their next turn."
    "name": "Heavy Glare"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/basilisk-fleemortals.png"
```
^statblock
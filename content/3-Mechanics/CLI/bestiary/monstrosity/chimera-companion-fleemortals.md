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
- Chimera Companion
---
# [Chimera Companion](3-Mechanics\CLI\bestiary\monstrosity/chimera-companion-fleemortals.md)
*Source: Flee, Mortals! p. 55*  

```statblock
"name": "Chimera Companion (FleeMortals)"
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
  - !!int "5"
  - !!int "12"
  - !!int "8"
"speed": "30 ft., fly 30 ft."
"saves":
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Bite)"
  - "desc": "The chimera makes a signature attack. On a hit, the attack imposes disadvantage\
      \ on the target's next attack roll made before the start of the chimera's next\
      \ turn."
    "name": "1st Level: Ram's Defense (2 Ferocity)"
  - "desc": "The chimera moves up to half their speed without provoking opportunity\
      \ attacks. If they end this movement on the ground, each creature within 5 feet\
      \ of them must succeed on a DC 10 plus PB Strength saving throw or be knocked\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "3rd Level: Lion's Leap (5 Ferocity)"
  - "desc": "The chimera spits an explosion of fire at a point they can see within\
      \ 60 feet of them. Each creature in a 10-foot-radius sphere centered on that\
      \ point must make a DC 10 plus PB Dexterity saving throw, taking PBd6 fire damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "5th Level: Volcanic Blow (8 Ferocity)"
"reactions":
  - "desc": "When the chimera's caregiver takes damage while within 60 feet of the\
      \ chimera, half the damage taken (rounded up) is transferred to the chimera."
    "name": "Protective Absorption (Recharges after a Short or Long Rest)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/chimera-companion-fleemortals.png"
```
^statblock
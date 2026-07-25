---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Abyssal Hyena Companion
---
# [Abyssal Hyena Companion](3-Mechanics\CLI\bestiary\fiend/abyssal-hyena-companion-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 159, Flee, Mortals! p. 123*  

```statblock
"name": "Abyssal Hyena Companion (WhereEvilLives)"
"size": "Medium"
"type": "fiend"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "12"
  - !!int "5"
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
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Bite)"
  - "desc": "The hyena makes a signature attack. On a hit, the target also has disadvantage\
      \ on the next Strength or Dexterity saving throw they make before the start\
      \ of their next turn."
    "name": "1st Level: Unbalancing Attack (2 Ferocity)"
  - "desc": "The hyena makes a signature attack with advantage. On a hit, the attack\
      \ deals an extra PB necrotic damage, and the hyena regains hit points equal\
      \ to the necrotic damage dealt."
    "name": "3rd Level: Gobbling Bite (5 Ferocity)"
  - "desc": "Each enemy within 30 feet of the hyena who can hear them must succeed\
      \ on a DC 10 plus PB Wisdom saving throw or take PBd4 psychic damage and be\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened) of the hyena until\
      \ the start of the hyena's next turn."
    "name": "5th Level: Cackle (8 Ferocity)"
"reactions":
  - "desc": "When the hyena's caregiver is hit with an attack and the hyena is within\
      \ 5 feet of the attacker, the hyena can make a signature attack against the\
      \ attacker."
    "name": "Blood Frenzy (Recharges after a Short or Long Rest)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/abyssal-hyena-companion-whereevillives.png"
```
^statblock
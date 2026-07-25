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
- Rotbeast Companion
---
# [Rotbeast Companion](3-Mechanics\CLI\bestiary\beast/rotbeast-companion-fleemortals.md)
*Source: Flee, Mortals! p. 304*  

```statblock
"name": "Rotbeast Companion (FleeMortals)"
"size": "Large"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "5"
  - !!int "12"
  - !!int "8"
"speed": "30 ft."
"saves":
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+1 plus PB"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "passive Perception 11"
"languages": ""
"traits":
  - "desc": "The rotbeast and their caregiver ignore mundane difficult terrain."
    "name": "Rotted Path"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Horns)"
  - "desc": "The rotbeast makes a signature attack. On a hit, the attack deals an\
      \ extra PB piercing damage, and the area within 5 feet of the target becomes\
      \ difficult terrain for the rotbeast's enemies until the start of the rotbeast's\
      \ next turn."
    "name": "1st Level: Tainting Attack (2 Ferocity)"
  - "desc": "The rotbeast moves up to their speed without provoking opportunity attacks,\
      \ then makes a signature attack. On a hit, the attack deals an extra PB bludgeoning\
      \ damage, and the target must succeed on a DC 10 plus PB Constitution saving\
      \ throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until the\
      \ start of the rotbeast's next turn."
    "name": "3rd Level: Rotting Hooves (5 Ferocity)"
  - "desc": "The rotbeast moves up to their speed without provoking opportunity attacks,\
      \ tainting the ground beneath their hooves and making it mundane difficult terrain\
      \ for their enemies until the start of the rotbeast's next turn. During this\
      \ move, the rotbeast can move through the space of Large or smaller creatures\
      \ as if they were difficult terrain. When a creature enters tainted ground for\
      \ the first time on a turn or starts their turn there, they must make a DC 10\
      \ plus PB Constitution saving throw, taking PBd8 poison damage on a failed save,\
      \ or half as much damage on a successful one."
    "name": "5th Level: Rotwake Charge (8 Ferocity)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/rotbeast-companion-fleemortals.png"
```
^statblock
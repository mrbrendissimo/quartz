---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ghoul
---
# [Ghoul](3-Mechanics\CLI\bestiary\undead/ghoul-fleemortals.md)
*Source: Flee, Mortals! p. 252*  

```statblock
"name": "Ghoul (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Skirmisher"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "6"
  - !!int "8"
  - !!int "5"
"speed": "40 ft., climb 40 ft."
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "the languages they knew in life"
"cr": "1"
"actions":
  - "desc": "The ghoul makes one Barbed Tongue attack and one Claws attack. If both\
      \ attacks hit the same creature, the target is [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the end of the target's next turn."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 15 ft., one target. Hit: 6\
      \ (1d6 + 3) slashing damage, and the target's speed is reduced by 10 feet until\
      \ the end of their next turn."
    "name": "Barbed Tongue"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
      \ + 3) slashing damage, and the target can't take reactions until the end of\
      \ their next turn."
    "name": "Claws"
"bonus_actions":
  - "desc": "The ghoul moves up to half their speed in a straight line. If the ghoul\
      \ moves at least 15 feet and ends this movement within 5 feet of a creature,\
      \ they have advantage on the next attack roll they make against that creature\
      \ until the end of the ghoul's next turn."
    "name": "Hungry Charge"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/undead/token/ghoul-fleemortals.png"
```
^statblock
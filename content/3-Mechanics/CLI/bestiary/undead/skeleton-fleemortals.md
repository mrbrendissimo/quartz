---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/artillery
statblock: inline
statblock-link: "#^statblock"
aliases:
- Skeleton
---
# [Skeleton](3-Mechanics\CLI\bestiary\undead/skeleton-fleemortals.md)
*Source: Flee, Mortals! p. 254*  

```statblock
"name": "Skeleton (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Artillery"
"alignment": "typically  Lawful Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "11"
  - !!int "9"
  - !!int "13"
  - !!int "4"
"speed": "30 ft."
"damage_vulnerabilities": "bludgeoning, force, thunder"
"damage_resistances": "piercing, slashing"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "the languages they knew in life"
"cr": "1/4"
"traits":
  - "desc": "The skeleton's weapon attacks are magical. They use their bones as ammunition\
      \ for their bone bow, regrowing used bones every dusk."
    "name": "Bone Weapons"
  - "desc": "If the skeleton is reduced to 0 hit points by bludgeoning, force, or\
      \ thunder damage, the skeleton is destroyed in an explosion of bone. Each creature\
      \ within 5 feet of them takes 4 piercing damage."
    "name": "Hail of Bones"
"actions":
  - "desc": "Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. Hit:\
      \ 4 (1d4 + 2) piercing, and if the target regains hit points before the start\
      \ of the skeleton's next turn, the number of hit points the target regains is\
      \ halved."
    "name": "Bone Bow"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
      \ + 2) slashing damage. If the target is a creature, they have disadvantage\
      \ on attack rolls until the end of this turn."
    "name": "Bone Knife"
"source":
  - "FleeMortals"
```
^statblock
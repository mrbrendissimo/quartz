---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Decrepit Skeleton
---
# [Decrepit Skeleton](3-Mechanics\CLI\bestiary\undead/decrepit-skeleton-fleemortals.md)
*Source: Flee, Mortals! p. 252*  

```statblock
"name": "Decrepit Skeleton (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Minion"
"alignment": "typically  Neutral Evil"
"ac": !!int "11"
"hp": !!int "6"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "13"
  - !!int "10"
  - !!int "7"
  - !!int "10"
  - !!int "4"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages they knew in life but can't speak"
"cr": "1/4"
"traits":
  - "desc": "The skeleton's weapon attacks are magical. They use their bones as ammunition\
      \ for their bone bow, regrowing used bones every dusk."
    "name": "Bone Weapons"
  - "desc": "If the skeleton takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the skeleton takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
      \ 1 piercing damage. If the target is a creature and three or more skeleton\
      \ minions joined the attack, the skeletons can choose another creature they\
      \ can see within 5 feet of the original target. The second target takes 2 piercing\
      \ damage."
    "name": "Bone Bow (Group Attack)"
  - "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 1 slashing\
      \ damage."
    "name": "Bone Knife (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/undead/token/decrepit-skeleton-fleemortals.png"
```
^statblock
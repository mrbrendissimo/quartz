---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/plant/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Thornblood
---
# [Thornblood](3-Mechanics\CLI\bestiary\plant/thornblood-fleemortals.md)
*Source: Flee, Mortals! p. 323*  

```statblock
"name": "Thornblood (FleeMortals)"
"size": "Gargantuan"
"type": "plant"
"subtype": "Controller"
"alignment": "typically  Neutral"
"ac": !!int "16"
"hp": !!int "324"
"hit_dice": "24d20 + 72"
"modifier": !!int "6"
"stats":
  - !!int "22"
  - !!int "23"
  - !!int "17"
  - !!int "11"
  - !!int "16"
  - !!int "8"
"speed": "30 ft., climb 30 ft."
"saves":
  - "constitution": !!int "9"
  - "wisdom": !!int "9"
"damage_resistances": "cold; lightning; bludgeoning, piercing, slashing from mundane\
  \ attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ flanked, [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 120 ft., passive Perception 13"
"languages": "Sylvan"
"cr": "20"
"traits":
  - "desc": "The thornblood is a mass of thick, thorny vines that grow from a Medium\
      \ humanoid corpse. When the thornblood is reduced to 0 hit points, they are\
      \ reduced to 1 hit point instead and retreat into the corpse that grew them.\n\
      \nThe thornblood becomes immune to all damage until the end of their next turn.\
      \ Additionally, until the thornblood finishes a long rest, their size becomes\
      \ Medium, their walking and climbing speeds become 60 feet, and they can't make\
      \ Throttle attacks or benefit from the Overgrowth trait."
    "name": "Corpse Retreat (1/Day)"
  - "desc": "The thornblood can move their vines through a space as narrow as 1 inch\
      \ wide without squeezing. The thornblood can occupy another creature's space\
      \ and vice versa."
    "name": "Overgrowth"
  - "desc": "The thornblood has advantage on saving throws against powers, spells,\
      \ and other supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "The thornblood makes four attacks using Vinerip, Throttle, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +12 to hit, reach 30 ft., one target. Hit: 20\
      \ (4d6 + 6) bludgeoning damage plus 11 (2d10) piercing damage, and the target\
      \ is pulled up to 30 feet toward the thornblood."
    "name": "Vinerip"
  - "desc": "Melee Weapon Attack: +12 to hit, reach 0 ft., one target in the thornblood's\
      \ space. Hit: 20 (4d6 + 6) piercing damage, and the target is entangled in\
      \ thorny vines. While entangled, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and moves with the thornblood, can't see outside their space, and takes 20\
      \ (4d6 + 6) piercing damage at the start of each of their turns. The target\
      \ or another creature within 5 feet of them can use their action to take 20\
      \ (4d6 + 6) slashing damage and make a DC 20 Strength check, freeing the target\
      \ on a success."
    "name": "Throttle"
  - "desc": "The thornblood must have at least one creature entangled to use this\
      \ action. Each creature entangled by the thornblood must make a DC 20 Constitution\
      \ saving throw, taking 55 (10d10) necrotic damage on a failed save, or half\
      \ as much damage on a successful one. Then the thornblood shoots a bolt of lightning\
      \ at each enemy within 60 feet of them who isn't entangled by them. Each target\
      \ must make a DC 20 Dexterity saving throw, taking 55 (10d10) lightning damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "From Life, Lightning (2/Day)"
"bonus_actions":
  - "desc": "The thornblood moves an entangled creature to a space occupied by the\
      \ thornblood that isn't also occupied by another creature or object."
    "name": "You're Mine"
"reactions":
  - "desc": "When an enemy ends their turn in the thornblood's space, the thornblood\
      \ attempts to pull them down. The target must make a DC 17 Dexterity saving\
      \ throw or fall [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Hostile Roots"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/plant/token/thornblood-fleemortals.webp"
```
^statblock
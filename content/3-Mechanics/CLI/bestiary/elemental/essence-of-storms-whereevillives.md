---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental/air
- ttrpg-cli/monster/type/elemental/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Essence of Storms
---
# [Essence of Storms](3-Mechanics\CLI\bestiary\elemental/essence-of-storms-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 297, Flee, Mortals! p. 92*  

```statblock
"name": "Essence of Storms (WhereEvilLives)"
"size": "Medium"
"type": "elemental"
"subtype": "air, Controller"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "17"
  - !!int "14"
  - !!int "9"
  - !!int "11"
  - !!int "13"
"speed": "20 ft., fly 60 ft. (hover)"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "lightning, poison, thunder"
"condition_immunities": "[dazed](/3-Mechanics/CLI/conditions.md#Dazed), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Auran, Common"
"cr": "5"
"actions":
  - "desc": "The essence makes two Wind Talons attacks. They can replace one attack\
      \ with a use of Bluster or Lightning Squall, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
      \ (2d6 + 3) piercing damage."
    "name": "Wind Talons"
  - "desc": "The essence unleashes a 30-foot cone of wind. Each creature in that area\
      \ must succeed on a DC 14 Strength saving throw or be moved up to 10 feet in\
      \ any direction."
    "name": "Bluster"
  - "desc": "The essence hurls a small lightning storm at a creature they can see\
      \ within 30 feet of them. The target must make a DC 14 Constitution saving throw.\
      \ On a failed save, the target takes 28 (8d6) lightning damage and is [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ for 1 minute (save ends at end of turn). On a successful save, they take half\
      \ as much damage and aren't [dazed](/3-Mechanics/CLI/conditions.md#Dazed)."
    "name": "Lightning Squall (3/Day)"
"bonus_actions":
  - "desc": "The essence imbues the power of air in themself or another Elemental\
      \ they can see within 30 feet of them, granting one of the following effects\
      \ of that Elemental's choice:\n\n- Rising Whirlwind. Each creature of the\
      \ Elemental's choice within 30 feet of them must make a DC 14 Strength saving\
      \ throw against a violent whirlwind. On a failed save, the target rises 10 feet\
      \ upward and is [restrained](/3-Mechanics/CLI/conditions.md#Restrained) for\
      \ 1 minute (save ends at end of turn). A target [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ in this way rises an additional 10 feet at the start of each of their turns.\
      \ Another creature who can reach the target can use an action to pull them free\
      \ of the effect, ending the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition for that creature. The whirlwind ends if the Elemental dies or chooses\
      \ to end it (no action required).  \n- Vortex Terrain. A vortex swirls around\
      \ the Elemental. For 1 minute, the area within 20 feet of the Elemental is difficult\
      \ terrain for enemies.  "
    "name": "Convocation of Air (1/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/essence-of-storms-whereevillives.png"
```
^statblock
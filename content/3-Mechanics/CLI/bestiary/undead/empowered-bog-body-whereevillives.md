---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/ambusher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Empowered Bog Body
---
# [Empowered Bog Body](3-Mechanics\CLI\bestiary\undead/empowered-bog-body-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 242*  

```statblock
"name": "Empowered Bog Body (WhereEvilLives)"
"size": "Medium"
"type": "undead"
"subtype": "Ambusher"
"alignment": "typically  Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "1"
"stats":
  - !!int "26"
  - !!int "12"
  - !!int "16"
  - !!int "5"
  - !!int "10"
  - !!int "6"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "blindsight 60 ft., passive Perception 12"
"languages": "understands the languages they knew in life but can't speak"
"cr": "3"
"traits":
  - "desc": "A creature who deals piercing or slashing damage to the bog body while\
      \ within 5 feet of them takes 3 (d6) acid damage."
    "name": "Acidic Blood"
"actions":
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 11\
      \ (1d6 + 8) bludgeoning damage. If the target is a Medium or smaller creature,\
      \ they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 18).\
      \ Until this grapple ends, the bog body can't make a Slam attack against another\
      \ target."
    "name": "Slam"
  - "desc": "Ranged Weapon Attack: +10 to hit, range 30 ft., one target. Hit:\
      \ 10 (1d4 + 8) bludgeoning damage plus 3 (d6) acid damage."
    "name": "Sling Mud"
  - "desc": "If the bog body is in swampy terrain, they can submerge themself beneath\
      \ the water and mud. While submerged, the bog body is heavily obscured.\n\n\
      If the bog body is grappling a target when they submerge, the target submerges\
      \ with them. While submerged, the target is heavily obscured, [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ and unable to breathe, and takes 4 (d8) acid damage at the start of each of\
      \ their turns.\n\nA bog body can resurface as a bonus action. When they do so,\
      \ a target they have [grappled](/3-Mechanics/CLI/conditions.md#Grappled) also\
      \ resurfaces."
    "name": "Submerge"
"source":
  - "WhereEvilLives"
```
^statblock
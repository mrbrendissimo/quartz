---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Deathhawk
---
# [Deathhawk](3-Mechanics\CLI\bestiary\beast/deathhawk-fleemortals.md)
*Source: Flee, Mortals! p. 39*  

```statblock
"name": "Deathhawk (FleeMortals)"
"size": "Medium"
"type": "beast"
"subtype": "Skirmisher"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d8 + 32"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "19"
  - !!int "11"
  - !!int "10"
  - !!int "9"
"speed": "10 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "understands Common but can't speak it"
"cr": "4"
"traits":
  - "desc": "Within a range of 5 miles, the deathhawk can sense the presence of Undead\
      \ or corpses that have been dead for less than 90 days; the deathhawk knows\
      \ the general direction these are in but not their exact locations. In addition,\
      \ the deathhawk has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks made to find Undead or corpses that have been dead for less than 90\
      \ days."
    "name": "Corpse Sense"
  - "desc": "The deathhawk doesn't provoke opportunity attacks when they fly out of\
      \ an enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "The deathhawk makes one Beak attack and one Wounding Talons attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
      \ (3d4 + 4) piercing damage."
    "name": "Beak"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
      \ (2d6 + 4) slashing damage. If the target is a creature who isn't a Construct\
      \ or an Undead, they gain a bleeding wound that lasts until they regain at least\
      \ 1 hit point. A bleeding creature loses 5 (d10) hit points for each bleeding\
      \ wound they have at the start of their turn. Any creature who can reach the\
      \ target can use an action to stanch all the target's wounds, ending the effect."
    "name": "Wounding Talons"
"bonus_actions":
  - "desc": "The deathhawk shrieks, and each enemy within 300 feet of the deathhawk\
      \ who can hear them must make a DC 14 Wisdom saving throw. Creatures who are\
      \ immune to the [frightened](/3-Mechanics/CLI/conditions.md#Frightened) condition\
      \ automatically succeed on this saving throw. On a failed save, a creature is\
      \ horrified for 1 minute (save ends at end of turn). While horrified, each time\
      \ the creature makes an attack roll or a saving throw, they must roll a d4 and\
      \ subtract the number rolled from the attack roll or saving throw.\n\nIf a creature's\
      \ saving throw is successful or the effect ends for them, they are immune to\
      \ the Bloodcurdling Shriek of all deathhawks for the next 24 hours."
    "name": "Bloodcurdling Shriek (Recharge 6)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/deathhawk-fleemortals.png"
```
^statblock
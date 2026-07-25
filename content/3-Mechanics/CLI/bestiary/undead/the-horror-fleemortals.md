---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Horror
---
# [The Horror](3-Mechanics\CLI\bestiary\undead/the-horror-fleemortals.md)
*Source: Flee, Mortals! p. 353*  

```statblock
"name": "The Horror (FleeMortals)"
"size": "Large"
"type": "undead"
"subtype": "Brute"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "8"
  - !!int "16"
  - !!int "10"
  - !!int "9"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "6"
  - "constitution": !!int "5"
  - "wisdom": !!int "1"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands Common but can't speak"
"cr": "1"
"traits":
  - "desc": "When the Horror dies, they begin to rupture in a vile explosion of viscera\
      \ and necrotic energy. The creature who reduced the Horror to 0 hit points can\
      \ make a DC 15 Charisma ([Persuasion](/3-Mechanics/CLI/skills.md#Persuasion))\
      \ check to appeal to Elyas's departing soul (no action required). On a successful\
      \ check, his soul transforms the explosion and each enemy of the Grave Order\
      \ within 30 feet of the Horror gains 7 (2d6) temporary hit points. On a failed\
      \ check (or if no check is made), each creature within 15 feet of the Horror\
      \ must make a DC 13 Dexterity saving throw, taking 4 (d8) acid damage plus 4\
      \ (d8) necrotic damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Dying Gasp"
"actions":
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
      \ + 4) slashing damage, or 13 (2d8 + 4) slashing damage against a [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ target."
    "name": "Spine Cleaver"
  - "desc": "Ranged Weapon Attack: +6 to hit, range 15 ft., one target. Hit: 7\
      \ (1d6 + 4) piercing damage. If the target is Medium or smaller, they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 14) and the Horror can pull the target up to 15 feet toward them.\n\
      \nUntil this grapple ends, the Horror can't make a Bone Hook attack against\
      \ another target."
    "name": "Bone Hook"
"bonus_actions":
  - "desc": "Each enemy within 10 feet of the Horror who can hear the Horror must\
      \ succeed on a DC 13 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the Horror for 1 minute (save ends at end of turn). If a creature's saving\
      \ throw is successful or the effect ends for them, the creature is immune to\
      \ the Horror's Valor's Death for 24 hours."
    "name": "Valor's Death"
"source":
  - "FleeMortals"
```
^statblock
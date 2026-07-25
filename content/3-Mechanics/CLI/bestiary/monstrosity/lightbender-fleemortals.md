---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/ambusher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lightbender
---
# [Lightbender](3-Mechanics\CLI\bestiary\monstrosity/lightbender-fleemortals.md)
*Source: Flee, Mortals! p. 180*  

```statblock
"name": "Lightbender (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Ambusher"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "102"
"hit_dice": "12d10 + 36"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "16"
  - !!int "6"
  - !!int "12"
  - !!int "8"
"speed": "50 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "5"
"traits":
  - "desc": "If the lightbender is subjected to an effect that allows them to make\
      \ a saving throw to take only half damage, they instead take no damage if they\
      \ succeed on the saving throw, and only half damage if they fail."
    "name": "Avoidance"
  - "desc": "If the lightbender moves at least 20 feet straight toward a creature\
      \ and then hits them with a Claw attack on the same turn, that target must succeed\
      \ on a DC 15 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ If the target is [prone](/3-Mechanics/CLI/conditions.md#Prone), the lightbender\
      \ can make one Bite attack against them as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "The lightbender makes one Bite attack and two Claw attacks, or uses their\
      \ Tail Whip twice."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
      \ + 4) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6\
      \ + 4) slashing damage."
    "name": "Claw"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 15 ft., one target. Hit: 7\
      \ (1d6 + 4) bludgeoning damage plus 7 (2d6) radiant damage."
    "name": "Tail Whip"
  - "desc": "The lightbender discharges the light absorbed in their mane into a brilliant,\
      \ mesmerizing display. Each creature within 15 feet of the lightbender must\
      \ succeed on a DC 14 Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by the lightbender for 1 minute. While [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ in this way, a creature is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ and has a speed of 0. If a creature [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ in this way takes damage or if someone else uses an action to shake the creature\
      \ out of their stupor, the condition ends for that creature."
    "name": "Hypnotic Mane (1/Day)"
"reactions":
  - "desc": "When the lightbender is hit by an attack, they can reveal that the attacker\
      \ is attacking a past visual imprint of the lightbender. The lightbender appears\
      \ in an unoccupied space they can see within 30 feet of their imprint, the attack\
      \ misses, then the imprint disappears. The lightbender can't use this reaction\
      \ if the attacker relies on senses other than sight, such as blindsight, or\
      \ if they can perceive illusions as false, as with truesight."
    "name": "Afterimage"
"source":
  - "FleeMortals"
```
^statblock
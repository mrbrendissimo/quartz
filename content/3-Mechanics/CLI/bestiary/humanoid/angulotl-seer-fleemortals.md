---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/angulotl
- ttrpg-cli/monster/type/humanoid/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Angulotl Seer
---
# [Angulotl Seer](3-Mechanics\CLI\bestiary\humanoid/angulotl-seer-fleemortals.md)
*Source: Flee, Mortals! p. 30*  

```statblock
"name": "Angulotl Seer (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "angulotl, Controller"
"alignment": "Any alignment"
"ac": !!int "13"
"hp": !!int "81"
"hit_dice": "18d6 + 18"
"modifier": !!int "3"
"stats":
  - !!int "7"
  - !!int "17"
  - !!int "12"
  - !!int "12"
  - !!int "18"
  - !!int "10"
"speed": "20 ft., climb 20 ft., swim 30 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+7"
"damage_immunities": "poison"
"senses": "darkvision 120 ft., truesight 60 ft., passive Perception 20"
"languages": "Angulotl"
"cr": "6"
"traits":
  - "desc": "The seer can breathe air and water."
    "name": "Amphibious"
  - "desc": "Creatures within 30 feet of the seer can't hide from the seer. Creatures\
      \ who can't be targeted by divination magic are immune to this effect."
    "name": "Third Eye"
  - "desc": "When a creature hits the seer with a melee attack while within 5 feet\
      \ of them or touches the seer, that creature takes 2 (d4) poison damage."
    "name": "Toxiferous"
"actions":
  - "desc": "Melee Spell Attack: +7 to hit, reach 5 ft., one target. Hit: 14 (4d6)\
      \ acid damage. If the target is a creature and they attack the seer before the\
      \ start of the seer's next turn, the target takes 14 (4d6) acid damage."
    "name": "Acid Grasp"
  - "desc": "The seer fires two magical beams of radiant energy, each beam targeting\
      \ a creature the seer can see within 120 feet of them. Each target must succeed\
      \ on a DC 15 Dexterity saving throw or take 13 (3d8) radiant damage and shed\
      \ dim light in a 10-foot radius for 1 minute (save ends at end of turn). While\
      \ shedding light in this way, attack rolls against the target have advantage,\
      \ the target can't benefit from being [invisible](/3-Mechanics/CLI/conditions.md#Invisible),\
      \ and they can't take the Hide action."
    "name": "Refulgent Beam"
  - "desc": "The seer creates a 5-foot-radius sphere filled with toxic gas in an unoccupied\
      \ space they can see within 60 feet of them. If undisturbed, this bubble lasts\
      \ for 1 minute then dissipates harmlessly. If a creature attacks the bubble,\
      \ touches it, enters its space, or otherwise disturbs it, the bubble bursts,\
      \ and each creature within 15 feet of it must make a DC 15 Constitution saving\
      \ throw, taking 27 (6d8) poison damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "Noxious Bubble (1/Day)"
  - "desc": "Each enemy within 60 feet of the seer who can hear them must succeed\
      \ on a DC 15 Wisdom saving throw or take 10 (3d6) psychic damage and be [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ for 1 minute (save ends at end of turn)."
    "name": "Psychedelic Drone (1/Day)"
"bonus_actions":
  - "desc": "The seer jumps a number of feet up to their walking speed."
    "name": "Hop"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/angulotl-seer-fleemortals.png"
```
^statblock
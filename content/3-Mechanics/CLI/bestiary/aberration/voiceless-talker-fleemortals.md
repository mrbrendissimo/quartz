---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Voiceless Talker
---
# [Voiceless Talker](3-Mechanics\CLI\bestiary\aberration/voiceless-talker-fleemortals.md)
*Source: Flee, Mortals! p. 282*  

```statblock
"name": "Voiceless Talker (FleeMortals)"
"size": "Medium"
"type": "aberration"
"subtype": "Controller"
"alignment": "typically  Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "19"
  - !!int "15"
  - !!int "14"
"speed": "30 ft., fly 30 ft."
"saves":
  - "constitution": !!int "5"
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "bludgeoning"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Deep Speech, Undercommon, telepathy 120 ft."
"cr": "7"
"actions":
  - "desc": "The voiceless talker manifests a power and makes one Tentacle or Psionic\
      \ Pistol attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 15\
      \ (2d10 + 4) psychic damage, and if the target is Large or smaller, they are\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 15)."
    "name": "Tentacle"
  - "desc": "Ranged Weapon Attack: +7 to hit, range 80/320 ft., one target. Hit:\
      \ 15 (2d10 + 4) force damage."
    "name": "Psionic Pistol"
  - "desc": "The voiceless talker psionically plunders the mind of a creature they\
      \ can see within 30 feet of them. The target must make a DC 15 Intelligence\
      \ saving throw. On a failed save, the target takes 22 (4d10) psychic damage,\
      \ and until they finish a long rest or die, their proficiency bonus is cumulatively\
      \ lowered by 1 and the voiceless talker gains a cumulative +2 bonus to damage\
      \ rolls. On a successful save, a target takes half as much damage and doesn't\
      \ have their proficiency bonus reduced.\n\nA creature whose proficiency bonus\
      \ drops to 0 can't form new thoughts or speak, and they have disadvantage on\
      \ ability checks, attack rolls, and saving throws."
    "name": "Memory Thief (4th-Order Power)"
  - "desc": "The voiceless talker shoots forth a 15-foot cone of pure psionic energy.\
      \ Each creature in the area must make a DC 15 Intelligence saving throw, taking\
      \ 28 (8d6) psychic damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Flay (3/Day; 5th-Order Power)"
  - "desc": "The voiceless talker projects a psionic image over their body, transforming\
      \ their appearance for 1 hour into that of a Medium creature they have seen.\
      \ When they manifest this power, they can also change the appearance of any\
      \ equipment they carry for the duration.\n\nThe changes wrought by this power\
      \ fail to hold up to physical inspection. A creature can use an action to inspect\
      \ the voiceless talker's appearance and make a DC 15 Intelligence ([Investigation](/3-Mechanics/CLI/skills.md#Investigation))\
      \ check, noticing the image is a projection on a success."
    "name": "Guise (3rd-Order Power)"
"reactions":
  - "desc": "When a creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by\
      \ the voiceless talker makes a saving throw against one of the voiceless talker's\
      \ powers, the voiceless talker momentarily weakens the creature and the creature\
      \ has disadvantage on the saving throw."
    "name": "Brain Drain"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/voiceless-talker-whereevillives.png"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/bugbear
- ttrpg-cli/monster/type/humanoid/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bugbear Channeler
---
# [Bugbear Channeler](3-Mechanics\CLI\bestiary\humanoid/bugbear-channeler-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 144, Flee, Mortals! p. 51*  

```statblock
"name": "Bugbear Channeler (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "bugbear, Controller"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "102"
"hit_dice": "12d8 + 48"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "18"
  - !!int "15"
  - !!int "16"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "6"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common, Goblin"
"cr": "7"
"traits":
  - "desc": "In addition to any other spells in this stat block, the channeler can\
      \ cast the following spells, using Charisma as the spellcasting ability (spell\
      \ save DC 15):\n\nAt will: [light](/3-Mechanics/CLI/spells/light-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [message](/3-Mechanics/CLI/spells/message-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
      \n1/day each: [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [disguise self](/3-Mechanics/CLI/spells/disguise-self-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [identify](/3-Mechanics/CLI/spells/identify-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
      \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
      \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action\
      \ (see spell description) |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "Allied Humanoids within 15 feet of the channeler who can see or hear\
      \ them have advantage on Wisdom and Charisma saving throws."
    "name": "Bugbear's Inspiration"
"actions":
  - "desc": "The channeler makes two Channeling Staff attacks."
    "name": "Multiattack"
  - "desc": "Melee Spell Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
      \ + 4) bludgeoning damage plus 9 (2d8) lightning damage. If the target is a\
      \ Large or smaller creature, the channeler can move them up to 10 feet horizontally."
    "name": "Channeling Staff"
  - "desc": "The channeler attempts to use primal magic to overload a creature they\
      \ can see within 60 feet of them. The target must make a DC 15 Constitution\
      \ saving throw as thorny vines erupt from their body and attempt to envelop\
      \ them. On a failed save, the target takes 27 (5d10) piercing damage and is\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained) until the vines are\
      \ destroyed. On a successful save, a target takes half as much damage and isn't\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained). A creature [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ in this way takes 5 (d10) piercing damage at the start of each of their turns.\
      \ The vines have AC 15, 10 hit points, and immunity to psychic damage."
    "name": "Vine Eruption (3/Day; 4th-Level Spell)"
  - "desc": "The channeler creates a 20-foot-radius sphere of electricity centered\
      \ on a point they can see within 120 feet of them. The sphere lasts for 1 minute.\
      \ When an enemy starts their turn in that area, they must succeed on a DC 15\
      \ Dexterity saving throw or take 27 (6d8) lightning damage. As a bonus action,\
      \ the channeler can move the sphere up to 20 feet."
    "name": "Ball Lightning (1/Day; 7th-Level Spell; Concentration)"
"reactions":
  - "desc": "When a creature the channeler can see within 30 feet of them is hit with\
      \ an attack, the channeler can create a barrier of magical force around that\
      \ target. Until the start of the channeler's next turn, the target gains a +5\
      \ bonus to AC, including against the triggering attack."
    "name": "Shared Shield (2/Day; 2nd-Level Spell)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/bugbear-channeler-whereevillives.png"
```
^statblock
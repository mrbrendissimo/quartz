---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/artillery
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sea Hag
---
# [Sea Hag](3-Mechanics\CLI\bestiary\fey/sea-hag-fleemortals.md)
*Source: Flee, Mortals! p. 139*  

```statblock
"name": "Sea Hag (FleeMortals)"
"size": "Medium"
"type": "fey"
"subtype": "Artillery"
"alignment": "typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft., swim 60 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "cold, lightning"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Aquan, Common, Sylvan"
"cr": "2"
"traits":
  - "desc": "In addition to any other spells in this stat block, the hag can cast\
      \ the following spells, using Charisma as the spellcasting ability (spell save\
      \ DC 13):\n\nAt will: [create or destroy water](/3-Mechanics/CLI/spells/create-or-destroy-water-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [disguise self](/3-Mechanics/CLI/spells/disguise-self-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
      \n3/day each: [control water](/3-Mechanics/CLI/spells/control-water-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [identify](/3-Mechanics/CLI/spells/identify-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
      \n1/day each: [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [legend lore](/3-Mechanics/CLI/spells/legend-lore-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
      \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
      \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action\
      \ (see spell description) |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "The hag can breathe both air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The hag makes one Lightning Strike attack and uses Dry Drowning."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. Hit: 10 (3d6) lightning damage."
    "name": "Lightning Strike"
  - "desc": "The hag chooses a creature they can see within 120 feet of them, making\
      \ the target feel as though their lungs are filling with water. The target must\
      \ succeed on a DC 13 Wisdom saving throw or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the start of the hag's next turn. A creature who can breathe water or\
      \ who doesn't need air automatically succeeds on this saving throw."
    "name": "Dry Drowning"
"bonus_actions":
  - "desc": "The hag creates a roiling storm with a 60-foot radius centered on themself\
      \ that moves with them and lasts for 1 minute. The hag has advantage on Lightning\
      \ Strike attacks against targets in that area, and those attacks deal an extra\
      \ 3 (d6) lightning damage."
    "name": "Sea Storm (1/Day; 3rd-Level Spell; Concentration)"
"reactions":
  - "desc": "When a creature the hag can see within 30 feet of them hits the hag with\
      \ an attack, that creature must succeed on a DC 13 Wisdom saving throw or be\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened) of the hag until the\
      \ end of the hag's next turn."
    "name": "Fearsome Glare"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fey/token/sea-hag-fleemortals.png"
```
^statblock
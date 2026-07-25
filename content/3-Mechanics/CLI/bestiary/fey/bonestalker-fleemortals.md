---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/ambusher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bonestalker
---
# [Bonestalker](3-Mechanics\CLI\bestiary\fey/bonestalker-fleemortals.md)
*Source: Flee, Mortals! p. 301*  

```statblock
"name": "Bonestalker (FleeMortals)"
"size": "Medium"
"type": "fey"
"subtype": "Ambusher"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "12"
  - !!int "11"
  - !!int "14"
  - !!int "20"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "blindsight 120 ft., passive Perception 15"
"languages": "Common, Sylvan"
"cr": "6"
"traits":
  - "desc": "In addition to any other spells in this stat block, the bonestalker can\
      \ cast the following spells, using Charisma as the spellcasting ability (spell\
      \ save DC 16):\n\nAt will: [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>\n\n3/day: [silent image](/3-Mechanics/CLI/spells/silent-image-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>\n\n| Superscript | Casting Time\
      \ |\n|-------------|--------------|\n| A | 1 action |\n| B | 1 bonus action\
      \ |\n| R | 1 reaction |\n| + | Longer than 1 action (see spell description)\
      \ |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "The bonestalker starts with 5 (2d4) skulls, which they can destroy to\
      \ fuel their actions and reactions.\n\nChoose or roll a d4 to determine each\
      \ skull's creature type: 1, Beast; 2, Fey; 3, Humanoid; 4, Monstrosity."
    "name": "Bones of the Lost"
  - "desc": "While the bonestalker possesses at least one skull, they have advantage\
      \ on saving throws against powers, spells, and other supernatural effects."
    "name": "Skull Resistance"
"actions":
  - "desc": "The bonestalker makes two Touch of the Felled or two Scream of the Forsaken\
      \ attacks, and they can use Grief of the Bygone."
    "name": "Multiattack"
  - "desc": "Melee Spell Attack: +8 to hit, reach 5 ft., one target. Hit: 12 (2d6\
      \ + 5) necrotic damage. The bonestalker can destroy a Humanoid or Monstrosity\
      \ skull to deal an extra 10 (3d6) psychic damage to the target."
    "name": "Touch of the Felled"
  - "desc": "Ranged Spell Attack: +8 to hit, range 60 ft., one target. Hit: 15\
      \ (3d6 + 5) psychic damage.\n\nThe bonestalker can destroy a Fey skull to force\
      \ the target to make a DC 16 Wisdom saving throw. On a failed save, the target\
      \ is [frightened](/3-Mechanics/CLI/conditions.md#Frightened) of the bonestalker\
      \ until the start of the bonestalker's next turn."
    "name": "Scream of the Forsaken"
  - "desc": "The bonestalker destroys two skulls of any type, creating a 15-foot-radius\
      \ sphere of magical darkness centered on a point they can see within 60 feet\
      \ of them.\n\nThe darkness spreads around corners and lasts for 1 minute.\n\n\
      A creature with darkvision can't see through this darkness, and mundane light\
      \ can't illuminate it. The bonestalker is unaffected by the darkness and has\
      \ advantage on attack rolls against creatures in the darkness.Any creature who\
      \ starts their turn in the darkness must make a DC 16 Wisdom saving throw, taking\
      \ 14 (4d6) psychic damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Grief of the Bygone"
"reactions":
  - "desc": "When the bonestalker is hit by an attack, they can destroy a Beast skull\
      \ to become [invisible](/3-Mechanics/CLI/conditions.md#Invisible) until the\
      \ end of their next turn."
    "name": "Power from the Conquered"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fey/token/bonestalker-fleemortals.png"
```
^statblock
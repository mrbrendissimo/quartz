---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Night Hag
---
# [Night Hag](3-Mechanics\CLI\bestiary\fey/night-hag-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 138*  

```statblock
"name": "Night Hag (WhereEvilLives)"
"size": "Medium"
"type": "fey"
"subtype": "Controller"
"alignment": "typically  Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "17"
  - !!int "19"
"speed": "30 ft., fly 40 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7 (+17 with pass without trace)"
"damage_resistances": "fire; necrotic; bludgeoning, piercing, slashing from mundane\
  \ attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Common, Infernal, Sylvan"
"cr": "5"
"traits":
  - "desc": "In addition to any other spells in this stat block, the hag can cast\
      \ the following spells, using Charisma as the spellcasting ability (spell save\
      \ DC 15):\n\nAt will: [alter self](/3-Mechanics/CLI/spells/alter-self-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [pass without trace](/3-Mechanics/CLI/spells/pass-without-trace-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
      \n3/day each: [dream](/3-Mechanics/CLI/spells/dream-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [legend lore](/3-Mechanics/CLI/spells/legend-lore-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [mirage arcane](/3-Mechanics/CLI/spells/mirage-arcane-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
      \n1/day: [scrying](/3-Mechanics/CLI/spells/scrying-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
      \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
      \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action\
      \ (see spell description) |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "The hag has advantage on saving throws against powers, spells, and other\
      \ supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "The hag makes two Dream Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 9 (1d10\
      \ + 4) slashing damage plus 3 (d6) psychic damage. If a target is hit by this\
      \ attack more than once on a turn, they must make a DC 15 Constitution saving\
      \ throw. On a failed save, the target falls [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)\
      \ for 1 minute (save ends at end of turn), until the target takes damage, or\
      \ until another creature who can reach the target uses their action to wake\
      \ them. Creatures who can't be supernaturally put to sleep automatically succeed\
      \ on this saving throw."
    "name": "Dream Claw"
  - "desc": "The hag releases magic dream dust in a 60-foot cone. Each creature must\
      \ succeed on a DC 15 Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ for 1 minute or until they deal damage to another creature. While [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ the creature sees all allies as enemies and all enemies as allies."
    "name": "Vicious Visions (1/Day; 6th-Level Spell)"
  - "desc": "The hag magically shrinks down to a height of 1 inch, becoming Tiny along\
      \ with any items they wear or carry. While Tiny, the hag has advantage on Dexterity\
      \ ([Stealth](/3-Mechanics/CLI/skills.md#Stealth)) checks made to hide, and they\
      \ can use a bonus action to enter the head of an [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)\
      \ Humanoid they can reach or to grow back to the hag's normal size. The hag's\
      \ game statistics otherwise remain the same.\n\nWhile the hag is inside a Humanoid's\
      \ head, that Humanoid is considered haunted by the hag, and the hag has total\
      \ cover against attacks and other effects outside the head. The hag can speak\
      \ telepathically to the haunted Humanoid, but the Humanoid is unaware of the\
      \ source of this telepathic speech. The haunted Humanoid can't gain any benefit\
      \ from rest unless the hag allows it, and when the Humanoid attempts to sleep,\
      \ the hag can fill the Humanoid's mind with nightmarish visions.\n\nThe hag\
      \ is expelled from the head and grows back to their normal size if the haunted\
      \ Humanoid is affected by a [dispel evil and good](/3-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md)\
      \ spell or similar supernatural effects, or if the hag chooses to exit the head\
      \ as a bonus action."
    "name": "Tiny Time"
"bonus_actions":
  - "desc": "The hag moves one [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)\
      \ creature they can see within 60 feet of them up to 30 feet horizontally."
    "name": "Sleepwalk"
"reactions":
  - "desc": "When a creature within 5 feet of the hag hits them with an attack, the\
      \ hag spits sleep dust at the attacker. The attacker must make a DC 15 Constitution\
      \ saving throw. On a failed save, until the end of the hag's next turn, the\
      \ attacker feels tremendously sleepy, they can't take reactions, and they have\
      \ disadvantage on attack rolls and saving throws. Creatures who can't be supernaturally\
      \ put to sleep are immune to this effect."
    "name": "Aren't You Tired?"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/fey/token/night-hag-fleemortals.png"
```
^statblock
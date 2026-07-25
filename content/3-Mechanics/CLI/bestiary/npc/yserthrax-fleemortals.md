---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Yserthrax
---
# [Yserthrax](3-Mechanics\CLI\bestiary\npc/yserthrax-fleemortals.md)
*Source: Flee, Mortals! p. 85*  

```statblock
"name": "Yserthrax (FleeMortals)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "Solo"
"alignment": "Neutral Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "420"
"hit_dice": "24d20 + 168"
"modifier": !!int "0"
"stats":
  - !!int "28"
  - !!int "10"
  - !!int "25"
  - !!int "22"
  - !!int "17"
  - !!int "18"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "constitution": !!int "14"
  - "wisdom": !!int "10"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+11"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+17"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+17"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+11"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [dazed](/3-Mechanics/CLI/conditions.md#Dazed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 120 ft., truesight 60 ft., passive Perception 27"
"languages": "Common, Deep Speech, Draconic"
"cr": "22"
"traits":
  - "desc": "Yserthrax can breathe air and water."
    "name": "Amphibious"
  - "desc": "Poison damage dealt by Yserthrax ignores damage resistance and treats\
      \ damage immunity as damage resistance. Whenever Yserthrax deals poison damage\
      \ to a creature who isn't a Construct or an Undead, that creature must succeed\
      \ on a DC 19 Constitution saving throw or be corrupted (save ends at end of\
      \ turn). The corruption lasts until cured by a cure ailment power, [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md)\
      \ spell, or similar supernatural effect.\n\nWhile corrupted, a creature takes\
      \ 14 (4d6) psychic damage at the start of each of their turns as their mind\
      \ and body are ravaged by reality-warping anomalies. If a creature dies while\
      \ corrupted, their body melts into a gruesome puddle, becoming a [gibbering\
      \ mouther](/3-Mechanics/CLI/bestiary/aberration/gibbering-mouther-fleemortals.md)\
      \ under Yserthrax's control."
    "name": "Corruption"
  - "desc": "When Yserthrax fails a saving throw, she can take 16 (3d10) necrotic\
      \ damage and succeed instead."
    "name": "Withering Resistance (3/Day)"
"actions":
  - "desc": "Yserthrax makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +16 to hit, reach 15 ft., one target. Hit: 20\
      \ (2d10 + 9) piercing damage plus 11 (2d10) poison damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 16\
      \ (2d6 + 9) slashing damage, and Yserthrax can move the target up to 15 feet\
      \ horizontally."
    "name": "Claw"
  - "desc": "Yserthrax exhales poison in a 90-foot cone. Each creature in that area\
      \ must make a DC 22 Constitution saving throw. On a failed save, a target takes\
      \ 56 (16d6) poison damage and is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the end of their next turn. On a successful save, a target takes half\
      \ as much damage and isn't [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)."
    "name": "Corrupting Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "Yserthrax magically aggravates a creature she can see within 60 feet\
      \ of her who is corrupted by her Corruption trait. The target must succeed on\
      \ a DC 19 Constitution saving throw or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the end of their next turn."
    "name": "Ulcerate"
"reactions":
  - "desc": "When a creature Yserthrax can see within 60 feet of her hits her with\
      \ an attack or succeeds on a saving throw, Yserthrax conjures a reality-warping\
      \ anomaly around them. The creature must choose to either take 10 (3d6) psychic\
      \ damage or to reroll the attack or a saving throw and use the new result."
    "name": "Eldritch Disruption"
"legendary_actions":
  - "desc": "Yserthrax has three villain actions. She can take each action once during\
      \ an encounter after an enemy's turn. She can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Yserthrax conjures three monoliths of otherworldly green crystal, which\
      \ grow out of the ground centered on three points she can see within 500 feet\
      \ of her. Each monolith is a 10-foot-radius, 60-foot-high cylinder with AC 19,\
      \ 100 hit points, and immunity to poison and psychic damage. The monoliths don't\
      \ block Yserthrax's vision. Each creature within 10 feet of a monolith other\
      \ than Yserthrax is vulnerable to psychic damage. When a monolith is destroyed,\
      \ each creature within 30 feet of it must make a DC 19 Wisdom saving throw,\
      \ taking 21 (6d6) psychic damage on a failed save, or half as much damage on\
      \ a successful one."
    "name": "Action 1: Summon Monoliths"
  - "desc": "Yserthrax bats her wings erratically, releasing foul energy that warps\
      \ space around her. Each creature within 60 feet of her must succeed on a DC\
      \ 19 Charisma saving throw or be teleported up to 120 feet to an unoccupied\
      \ space Yserthrax can see."
    "name": "Action 2: Spatial Alteration"
  - "desc": "Yserthrax unleashes an eldritch scream, piercing the mind of each enemy\
      \ she can see within 120 feet of her. Each target must make a DC 19 Wisdom saving\
      \ throw, taking 77 (14d10) psychic damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Action 3: Elder Scream"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/yserthrax-fleemortals.png"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/retainer
- ttrpg-cli/monster/type/undead/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wight Deathguard
---
# [Wight Deathguard](3-Mechanics\CLI\bestiary\undead/wight-deathguard-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 235, Flee, Mortals! p. 256*  

```statblock
"name": "Wight Deathguard (WhereEvilLives)"
"size": "Medium"
"type": "undead"
"subtype": "undead, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "10"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "name": "Strength"
    "desc": "+PB"
  - "name": "Dexterity"
    "desc": "+PB"
  - "name": "Constitution"
    "desc": "+PB"
  - "name": "Intelligence"
    "desc": "+PB"
  - "name": "Wisdom"
    "desc": "+PB"
  - "name": "Charisma"
    "desc": "+PB"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3 plus PB"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+0 plus PB"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": "the languages they knew in life"
"actions":
  - "desc": "Melee Attack Roll: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d8 plus PB slashing damage. Beginning at 7th level, the deathguard can make\
      \ this attack twice, instead of once, when they take the Attack action on their\
      \ turn."
    "name": "Signature Attack (Longsword)"
  - "desc": "As a reaction to an ally the deathguard can see within 5 feet of them\
      \ being hit with an attack, the deathguard redirects the attack to themself,\
      \ potentially causing the attack to miss. If the attacker is within 5 feet of\
      \ the deathguard, the deathguard can make a signature attack against the attacker."
    "name": "3rd Level: Blood for Blood (3/Day)"
  - "desc": "As an action, the deathguard shrouds themself in dark energy. The deathguard\
      \ regains PBd6 hit points, and each enemy within 5 feet of the deathguard must\
      \ make a DC 10 plus PB Wisdom saving throw. On a failed save, a target takes\
      \ PBd6 necrotic damage. On a successful save, a target takes half as much damage."
    "name": "5th Level: Soul Thief (3/Day)"
  - "desc": "As an action, the deathguard moves up to their speed without provoking\
      \ opportunity attacks. Each ally the deathguard passes within 5 feet of during\
      \ the move can use a reaction to move up to their speed in the same direction\
      \ as the deathguard without provoking opportunity attacks. Until the start of\
      \ the deathguard's next turn, attacks against these allies have disadvantage."
    "name": "7th Level: This Way! (3/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/undead/token/wight-deathguard-whereevillives.png"
```
^statblock
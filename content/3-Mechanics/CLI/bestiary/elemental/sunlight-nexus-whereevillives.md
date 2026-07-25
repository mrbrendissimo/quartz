---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/air
- ttrpg-cli/monster/type/elemental/fire
- ttrpg-cli/monster/type/elemental/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sunlight Nexus
---
# [Sunlight Nexus](3-Mechanics\CLI\bestiary\elemental/sunlight-nexus-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 99*  

```statblock
"name": "Sunlight Nexus (WhereEvilLives)"
"size": "Large"
"type": "elemental"
"subtype": "air, fire, Support"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "152"
"hit_dice": "16d10 + 64"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "15"
  - !!int "19"
  - !!int "14"
  - !!int "16"
  - !!int "20"
"speed": "40 ft., fly 90 ft."
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+6"
"damage_resistances": "fire, radiant"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Common, Primordial"
"cr": "12"
"traits":
  - "desc": "The nexus sheds bright sunlight in a 120-foot radius and dim light for\
      \ another 120 feet."
    "name": "Corona"
"actions":
  - "desc": "The nexus makes three Solar Arc attacks. They can replace one attack\
      \ with a use of Heavenly Collapse or Rejuvenating Flare, if available."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 30 ft.,\
      \ one target. Hit: 18 (2d12 + 5) radiant damage."
    "name": "Solar Arc"
  - "desc": "The nexus shines harsh light on an enemy they can see within 60 feet\
      \ of them. Each ally of the nexus within 5 feet of the target regains 20 hit\
      \ points, and the target must succeed on a DC 17 Constitution saving throw or\
      \ lose any damage resistances they have and be [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ for 1 minute (save ends at end of turn)."
    "name": "Heavenly Collapse (2/Day)"
  - "desc": "One ally the nexus can see within 30 feet of them is bathed in rejuvenating\
      \ light. The ally regains 27 (5d10) hit points, and if they are [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ [dazed](/3-Mechanics/CLI/conditions.md#Dazed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
      \ or [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), those conditions end\
      \ for them."
    "name": "Rejuvenating Flare (1/Day)"
"bonus_actions":
  - "desc": "The nexus imbues the power of sunlight in themself or another Elemental\
      \ they can see within 30 feet of them, granting one of the following effects\
      \ of that Elemental's choice:\n\n- Healing Radiance. The Elemental regains\
      \ 30 hit points. Until the end of the nexus's next turn, the Elemental refracts\
      \ shimmering light, and creatures within 10 feet of them who aren't Elementals\
      \ are [blinded](/3-Mechanics/CLI/conditions.md#Blinded).  \n- Protective Light.\
      \ Four brilliant motes orbit the Elemental for 1 minute. When the Elemental\
      \ deals damage to a creature with an attack, the Elemental can extinguish one\
      \ mote (no action required) to deal an extra 14 (4d6) radiant damage to that\
      \ creature.  "
    "name": "Convocation of Sunlight (2/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
```
^statblock
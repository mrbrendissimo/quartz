---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Empyrean Stag
---
# [Empyrean Stag](3-Mechanics\CLI\bestiary\celestial/empyrean-stag-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 243, Flee, Mortals! p. 303*  

```statblock
"name": "Empyrean Stag (WhereEvilLives)"
"size": "Large"
"type": "celestial"
"subtype": "Support"
"alignment": "typically  Neutral Good"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "187"
"hit_dice": "22d10 + 66"
"modifier": !!int "3"
"stats":
  - !!int "24"
  - !!int "16"
  - !!int "16"
  - !!int "18"
  - !!int "20"
  - !!int "20"
"speed": "60 ft."
"saves":
  - "dexterity": !!int "8"
  - "wisdom": !!int "10"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "radiant"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 20"
"languages": "all, telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "The stag has advantage on saving throws against powers, spells, and other\
      \ supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "The stag makes three Ram or Lightburst attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 25\
      \ (4d8 + 7) piercing damage."
    "name": "Ram"
  - "desc": "Ranged Spell Attack: +10 to hit, range 120 ft., one target. Hit:\
      \ 18 (3d8 + 5) radiant damage, and the target is outlined in a golden light,\
      \ giving attack rolls against them advantage until the start of the stag's next\
      \ turn."
    "name": "Lightburst"
  - "desc": "The stag calls down a magical shower of stars on an area that is 60 feet\
      \ long and 5 feet wide within 120 feet of the stag. Each enemy in that area\
      \ must make a DC 18 Dexterity saving throw, taking 28 (8d6) radiant damage on\
      \ a failed save, or half as much damage on a successful one. Each other willing\
      \ creature in that area regains 15 hit points.\n\nThe stars then create a 10-foot-high\
      \ wall of opaque radiant light in that area. Each creature in the wall's space\
      \ is pushed out of it by the shortest route. The creature chooses which side\
      \ of the wall to end up on. The wall lasts for 1 minute or until the stag is\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated) or dies. Any\
      \ enemy who enters the wall of light for the first time on a turn must make\
      \ a DC 18 Constitution saving throw, taking 14 (4d6) radiant damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Starcall (1/Day)"
"bonus_actions":
  - "desc": "The stag infuses radiant energy into a willing creature they can see\
      \ within 60 feet of them. That creature deals an extra 5 radiant damage with\
      \ weapon attacks until the start of the stag's next turn."
    "name": "Starlight Infusion"
"reactions":
  - "desc": "When the stag or a creature they can see within 30 feet of them takes\
      \ damage, the stag magically creates a protective barrier around that creature.\
      \ The barrier reduces that damage to the protected creature by 20, then vanishes."
    "name": "Nature's Ward"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/celestial/token/empyrean-stag-whereevillives.png"
```
^statblock
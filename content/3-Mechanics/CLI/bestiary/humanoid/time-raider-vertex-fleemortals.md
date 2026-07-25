---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/humanoid/support
- ttrpg-cli/monster/type/humanoid/time-raider
statblock: inline
statblock-link: "#^statblock"
aliases:
- Time Raider Vertex
---
# [Time Raider Vertex](3-Mechanics\CLI\bestiary\humanoid/time-raider-vertex-fleemortals.md)
*Source: Flee, Mortals! p. 232*  

```statblock
"name": "Time Raider Vertex (FleeMortals)"
"size": "Large"
"type": "humanoid"
"subtype": "time raider, Support"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "psionic power armor"
"hp": !!int "153"
"hit_dice": "18d10 + 54"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "9"
  - !!int "16"
  - !!int "19"
  - !!int "16"
  - !!int "10"
"speed": "0 ft., fly 30 ft. (hover)"
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "6"
  - "intelligence": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 19"
"languages": "Common, Kuran'zoi, telepathy 120 ft."
"cr": "7"
"traits":
  - "desc": "The vertex is immune to any effect that would sense their emotions, read\
      \ their thoughts, reveal they are lying, or reveal their alignment or location."
    "name": "Psychic Scar"
"actions":
  - "desc": "The vertex makes two Psionic Slam attacks."
    "name": "Multiattack"
  - "desc": "Melee Power Attack: +7 to hit, reach 5 ft., one target. Hit: 11 (2d6\
      \ + 4) bludgeoning damage plus 7 (2d6) psychic damage, and the next attack roll\
      \ against the target made before the start of the vertex's next turn has advantage."
    "name": "Psionic Slam"
  - "desc": "The vertex chooses a point in a precise location they have seen (in person\
      \ or otherwise) on any plane of existence. A shimmering 10-foot-diameter portal\
      \ leading to that location appears in an unoccupied space within 5 feet of the\
      \ vertex. Each creature who touches the portal is instantly teleported to the\
      \ nearest unoccupied space at the chosen location. The portal lasts until the\
      \ vertex dies, uses this action again, dismisses the portal as an action, or\
      \ is transported by the portal."
    "name": "Split Space (2/Day)"
"bonus_actions":
  - "desc": "The vertex emits invigorating psionic energy. Each time raider within\
      \ 60 feet of the vertex can use their reaction to move up to half their speed."
    "name": "Invigorated March (3rd-Order Power)"
"reactions":
  - "desc": "When another Medium or smaller creature the vertex can see within 120\
      \ feet of them takes damage, that damage is reduced by 15."
    "name": "Kinetic Defense Field"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/time-raider-vertex-fleemortals.png"
```
^statblock
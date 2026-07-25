---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental/minion
- ttrpg-cli/monster/type/elemental/water
statblock: inline
statblock-link: "#^statblock"
aliases:
- Water Spark
---
# [Water Spark](3-Mechanics\CLI\bestiary\elemental/water-spark-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 301, Flee, Mortals! p. 99*  

```statblock
"name": "Water Spark (WhereEvilLives)"
"size": "Medium"
"type": "elemental"
"subtype": "water, Minion"
"alignment": "Any alignment"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "27"
"modifier": !!int "4"
"stats":
  - !!int "20"
  - !!int "18"
  - !!int "16"
  - !!int "9"
  - !!int "16"
  - !!int "11"
"speed": "30 ft., fly 30 ft., swim 50 ft."
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Aquan, Common"
"cr": "20"
"traits":
  - "desc": "If the spark takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the spark takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "If an enemy starts their turn within 5 feet of three or more water sparks,\
      \ the enemy must succeed on a Strength saving throw or have their speed reduced\
      \ to 0. The DC for this saving throw equals 14 plus the number of water sparks\
      \ within 5 feet of the enemy."
    "name": "Whirlpool Suction"
"actions":
  - "desc": "Melee  or Ranged Spell Attack: +11 to hit, reach 5 ft. or range 30\
      \ ft., one target. Hit: 10 bludgeoning damage, and if the attack was made\
      \ by more than one spark, the target must succeed on a Dexterity saving throw\
      \ or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone) and be unable\
      \ to stand up until the end of the sparks' next turn. The DC for this saving\
      \ throw equals 14 plus the number of sparks who joined the attack."
    "name": "Whelming Wave (Group Attack)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
```
^statblock
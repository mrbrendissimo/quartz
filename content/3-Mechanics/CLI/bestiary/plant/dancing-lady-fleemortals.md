---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/plant/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Dancing Lady
---
# [Dancing Lady](3-Mechanics\CLI\bestiary\plant/dancing-lady-fleemortals.md)
*Source: Flee, Mortals! p. 302*  

```statblock
"name": "Dancing Lady (FleeMortals)"
"size": "Huge"
"type": "plant"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "161"
"hit_dice": "14d12 + 70"
"modifier": !!int "-1"
"stats":
  - !!int "22"
  - !!int "8"
  - !!int "20"
  - !!int "10"
  - !!int "16"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "3"
  - "wisdom": !!int "7"
"damage_vulnerabilities": "fire"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), flanked, [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 120 ft. (blind beyond this radius), passive Perception 13"
"languages": "understands Druidic and Sylvan but can't speak"
"cr": "9"
"traits":
  - "desc": "The dancing lady has three spinning flowers resembling life-sized dancing\
      \ Humanoids. Each flower has AC 16, 5 hit points, vulnerability to fire damage,\
      \ and immunity to psychic damage. Attack rolls against these whirling blooms\
      \ have disadvantage. Destroying a flower deals no damage to the dancing lady,\
      \ who regrows destroyed flowers at the end of their turn."
    "name": "Dancing Flowers"
"actions":
  - "desc": "The dancing lady makes two Slam attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 25\
      \ (3d12 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "For each flower the dancing lady has, they can choose one creature they\
      \ can see within 60 feet of them. Each target must make a DC 17 Strength saving\
      \ throw as a dancing flower sweeps toward them. On a failed save, a creature\
      \ takes 18 (4d8) psychic damage and is moved to an unoccupied space within 60\
      \ feet of the dancing lady. On a successful save, a creature takes half as much\
      \ damage and isn't moved."
    "name": "Blood-Red Waltz"
  - "desc": "For each flower the dancing lady has, they can choose one creature they\
      \ can see within 60 feet of them. Each target must make a DC 17 Dexterity saving\
      \ throw as a dancing flower whirls them into a dance. On a failed save, a creature\
      \ takes 17 (5d6) bludgeoning damage and is [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the start of the dancing lady's next turn. On a successful save, a creature\
      \ takes half as much damage and isn't [dazed](/3-Mechanics/CLI/conditions.md#Dazed)."
    "name": "Disarming Quickstep"
  - "desc": "The dancing lady's flowers pirouette and emit acrid mist. Enemies within\
      \ 120 feet of the dancing lady who can smell the mist must make a DC 17 Wisdom\
      \ saving throw. On a failed save, a creature becomes [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the dancing lady for 1 minute (save ends at end of turn)."
    "name": "Ballet of Terror (1/Day)"
"reactions":
  - "desc": "When a creature the dancing lady can see hits the dancing lady with an\
      \ attack, the dancing lady causes the attack to hit one of their flowers instead."
    "name": "Somber Dirge"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/plant/token/dancing-lady-fleemortals.png"
```
^statblock
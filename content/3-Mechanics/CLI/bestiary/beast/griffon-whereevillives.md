---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Griffon
---
# [Griffon](3-Mechanics\CLI\bestiary\beast/griffon-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 102, Flee, Mortals! p. 135*  

```statblock
"name": "Griffon (WhereEvilLives)"
"size": "Large"
"type": "beast"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "57"
"hit_dice": "6d10 + 24"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "6"
  - !!int "14"
  - !!int "8"
"speed": "30 ft., fly 60 ft."
"saves":
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The griffon has advantage on ability checks and saving throws against\
      \ being knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Steady"
  - "desc": "If the griffon flies more than 20 feet in a straight line toward their\
      \ target and then hits them with a Claw attack on the same turn, the target\
      \ is [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 14). While\
      \ the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled) in this\
      \ way, the griffon has advantage on Beak attacks against the target but can't\
      \ make Claw attacks. Grappling a Medium or smaller creature imposes no penalty\
      \ on the griffon's speed."
    "name": "Swoop"
"actions":
  - "desc": "The griffon makes one Beak attack, and they can make one Claw attack,\
      \ use Buffet, or use Piercing Cry."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
      \ + 4) piercing damage."
    "name": "Beak"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (2d4\
      \ + 4) slashing damage."
    "name": "Claw"
  - "desc": "The griffon beats their wings in mighty gusts of wind. Each creature\
      \ not [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by the griffon within\
      \ a 30-foot cone originating from the griffon must make a DC 14 Strength saving\
      \ throw. On a failed save, a creature takes 5 (2d4) bludgeoning damage, is pushed\
      \ 5 feet away from the griffon, and is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Buffet"
  - "desc": "The griffon lets out an earsplitting screech. Each enemy within 60 feet\
      \ of the griffon who can hear them must succeed on a DC 12 Wisdom saving throw\
      \ or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened) of the griffon\
      \ for 1 minute (save ends at end of turn). If a creature's saving throw is successful\
      \ or the effect ends for them, they are immune to the Piercing Cry of all griffons\
      \ for the next 24 hours."
    "name": "Piercing Cry"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/griffon-fleemortals.png"
```
^statblock
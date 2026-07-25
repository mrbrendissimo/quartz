---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Scyza
---
# [Scyza](3-Mechanics\CLI\bestiary\monstrosity/scyza-fleemortals.md)
*Source: Flee, Mortals! p. 212*  

```statblock
"name": "Scyza (FleeMortals)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "108"
"hit_dice": "8d20 + 24"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "9"
  - !!int "17"
  - !!int "5"
  - !!int "11"
  - !!int "7"
"speed": "40 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "5"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": ""
"cr": "4"
"traits":
  - "desc": "The scyza deals double damage to objects and structures."
    "name": "Siege Monster"
  - "desc": "While wearing a war harness, the scyza can carry up to thirty-six Medium\
      \ or smaller creatures."
    "name": "War Harness"
"actions":
  - "desc": "The scyza makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 12\
      \ (2d6 + 5) slashing damage, and the target is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Claw"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 20 ft., one target. Hit: 14\
      \ (2d8 + 5) bludgeoning damage. If the target is on top of the scyza, the target\
      \ falls off and lands [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Tail Whip"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 23\
      \ (4d8 + 5) bludgeoning damage, and if the target is a creature who can hear,\
      \ they are [dazed](/3-Mechanics/CLI/conditions.md#Dazed) until the end of their\
      \ next turn by the crest's deep ringing."
    "name": "Head Crest"
  - "desc": "The scyza claws at the ground in a flurry. Each creature of the scyza's\
      \ choice within 5 feet of them must make a DC 15 Dexterity saving throw. On\
      \ a failed save, a creature takes 13 (3d8) slashing damage, is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone),\
      \ and is [blinded](/3-Mechanics/CLI/conditions.md#Blinded) by a cloud of dust\
      \ until the start of the scyza's next turn. On a successful save, a creature\
      \ takes half as much damage and isn't knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ or [blinded](/3-Mechanics/CLI/conditions.md#Blinded)."
    "name": "Claw Twister (Recharge 6)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/scyza-whereevillives.png"
```
^statblock
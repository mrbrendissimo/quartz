---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/plant/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Weeping Willow
---
# [Weeping Willow](3-Mechanics\CLI\bestiary\plant/weeping-willow-fleemortals.md)
*Source: Flee, Mortals! p. 317*  

```statblock
"name": "Weeping Willow (FleeMortals)"
"size": "Huge"
"type": "plant"
"subtype": "Controller"
"alignment": "typically  Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "84"
"hit_dice": "8d12 + 32"
"modifier": !!int "-1"
"stats":
  - !!int "20"
  - !!int "8"
  - !!int "18"
  - !!int "10"
  - !!int "14"
  - !!int "16"
"speed": "15 ft."
"damage_resistances": "bludgeoning, piercing"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Elvish, Sylvan"
"cr": "4"
"traits":
  - "desc": "While the willow remains motionless, they are indistinguishable from\
      \ a normal willow tree."
    "name": "False Appearance"
  - "desc": "If the willow takes fire damage, they catch fire and take 7 (2d6) fire\
      \ damage at the start of each of their turns for 1 minute. The effect ends early\
      \ if the willow takes cold damage or a creature uses an action to extinguish\
      \ the flames."
    "name": "Flammable"
"actions":
  - "desc": "The willow makes two Frenzied Branch attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 30 ft., one target. Hit: 12\
      \ (2d6 + 5) bludgeoning damage. If the willow is on fire, this attack deals\
      \ an extra 3 (d6) fire damage."
    "name": "Frenzied Branch"
  - "desc": "Roots erupt from a point on the ground the willow can see within 60 feet\
      \ of them. Each creature in a 10-foot sphere centered on that point must succeed\
      \ on a DC 14 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and moved up to 30 feet toward the willow, taking 4 (d8) bludgeoning damage\
      \ for every 10 feet moved."
    "name": "Tugging Roots"
  - "desc": "The willow showers salty droplets on their bower. Each creature within\
      \ 15 feet of the willow must succeed on a DC 14 Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by the willow (save ends at end of turn). While [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ in this way, a creature can't willingly move more than 15 feet away from the\
      \ willow. If a creature [charmed](/3-Mechanics/CLI/conditions.md#Charmed) in\
      \ this way takes damage, the effect ends for them."
    "name": "Willow's Tears"
"reactions":
  - "desc": "When a creature within 5 feet of the willow deals slashing damage to\
      \ the willow, the willow attempts to turn the creature into a tree. The target\
      \ must succeed on a DC 14 Constitution saving throw or their feet begin to transform\
      \ into tree roots and they are [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ A creature [restrained](/3-Mechanics/CLI/conditions.md#Restrained) in this\
      \ way must repeat the saving throw at the end of their next turn. On a successful\
      \ save, the effect ends. On a failed save, they are transformed into a wooden\
      \ tree and are [petrified](/3-Mechanics/CLI/conditions.md#Petrified). A creature\
      \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified) in this way resembles\
      \ a normal tree of the same size as that creature, except the creature's face\
      \ appears carved into the trunk. If the willow dies, the petrification ends\
      \ and the creature reverts to their true form. A cure ailment power or [lesser\
      \ restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md) spell also\
      \ ends this effect."
    "name": "Tree Transformation"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/plant/token/weeping-willow-fleemortals.png"
```
^statblock
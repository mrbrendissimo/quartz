---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Otyugh
---
# [Otyugh](3-Mechanics\CLI\bestiary\aberration/otyugh-fleemortals.md)
*Source: Flee, Mortals! p. 216*  

```statblock
"name": "Otyugh (FleeMortals)"
"size": "Large"
"type": "aberration"
"subtype": "Controller"
"alignment": "typically  Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "9d10 + 36"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "19"
  - !!int "6"
  - !!int "13"
  - !!int "6"
"speed": "45 ft. (see adjustable appendages)"
"saves":
  - "constitution": !!int "7"
"damage_resistances": "acid, poison"
"condition_immunities": "flanked, [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft. (see adjustable appendages), passive Perception 11"
"languages": "Otyugh"
"cr": "5"
"traits":
  - "desc": "The otyugh has seven adjustable appendages, which they can convert into\
      \ other appendages using their Transform bonus action. In their natural state,\
      \ the otyugh has one eyestalk, three legs, and three tentacles. These appendages\
      \ grant the following benefits:\n\n- Eyestalks. The otyugh's first eyestalk\
      \ gives them darkvision out to a range of 60 feet and immunity to the [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ condition, and each additional eyestalk increases their darkvision's range\
      \ by 60 feet. If the otyugh has no eyestalks, they are [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ and lose immunity to the [flanked](/3-Mechanics/CLI/conditions.md#Flanked)\
      \ condition.  \n- Legs. Each leg gives the otyugh a cumulative walking speed\
      \ of 15 feet.  \n- Tentacles. The otyugh's number of tentacles determine\
      \ how many attacks they can make with Multiattack and how many creatures they\
      \ can grapple with Tentacle Slam.  "
    "name": "Adjustable Appendages"
  - "desc": "The otyugh can magically transmit simple messages and images to any creature\
      \ within 120 feet of them that can understand a language. This form of telepathy\
      \ doesn't allow the receiving creature to telepathically respond."
    "name": "Limited Telepathy"
  - "desc": "At the start of each of the otyugh's turns, each creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by the otyugh has their hit point maximum reduced by 5 (d10) for 1 hour. The\
      \ otyugh regains the same number of hit points. This effect can't reduce a creature's\
      \ hit point maximum below their current hit points."
    "name": "Rot Leech"
  - "desc": "The otyugh ignores difficult terrain. They also have advantage on Dexterity\
      \ ([Stealth](/3-Mechanics/CLI/skills.md#Stealth)) checks made to hide in piles\
      \ of refuse."
    "name": "Trash Traversal"
  - "desc": "A creature who starts their turn within 10 feet of the otyugh must succeed\
      \ on a DC 15 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the start of the creature's next turn."
    "name": "Vile Stench"
"actions":
  - "desc": "The otyugh makes one Tentacle Slam attack for each tentacle they currently\
      \ have (see Adjustable Appendages)."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 21\
      \ (4d8 + 3) piercing damage, and the target must succeed on a DC 15 Constitution\
      \ saving throw or be diseased with otyuck. A creature with otyuck can't take\
      \ the Dash action and their speed is halved."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 7\
      \ (1d8 + 3) bludgeoning damage plus 3 (d6) piercing damage. If the target is\
      \ Medium or smaller, they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 13) and [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ until the grapple ends. The otyugh can grapple one target for each tentacle\
      \ they currently have."
    "name": "Tentacle Slam"
"bonus_actions":
  - "desc": "The otyugh converts one of their Adjustable Appendages into an eyestalk,\
      \ leg, or tentacle."
    "name": "Transform"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/otyugh-fleemortals.png"
```
^statblock
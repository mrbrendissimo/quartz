---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/kobold
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kobold Artifex
---
# [Kobold Artifex](3-Mechanics\CLI\bestiary\humanoid/kobold-artifex-fleemortals.md)
*Source: Flee, Mortals! p. 172*  

```statblock
"name": "Kobold Artifex (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold, Controller"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "49"
"hit_dice": "14d6"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "15"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "2"
"traits":
  - "desc": "The artifex gains a +1 bonus to AC while within 5 feet of at least one\
      \ ally who also has this trait, is wielding a shield, and isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ or [prone](/3-Mechanics/CLI/conditions.md#Prone). To benefit from this trait,\
      \ the artifex must be wielding a shield."
    "name": "Shield? Shield!"
"actions":
  - "desc": "The artifex makes one Chain Hook attack and uses Activate Trap, if available."
    "name": "Multiattack"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 15/30 ft., one target. Hit:\
      \ 4 (1d4 + 2) piercing damage, and if the target is a Large or smaller creature,\
      \ they must succeed on a DC 12 Strength saving throw or be pulled up to 15 feet\
      \ toward the artifex."
    "name": "Chain Hook"
  - "desc": "The artifex activates one of the following hidden traps; the artifex\
      \ can't use the same trap two rounds in a row:"
    "name": "Activate Trap (3/Day)"
  - "desc": "The artifex chooses a point on the ground that they can see within 60\
      \ feet of them, opening a concealed 15-foot-square trapdoor on the ground centered\
      \ on that point to reveal a 10-foot-deep pit trap lined with spikes. Creatures\
      \ on the ground in the trapdoor's area must make a DC 12 Dexterity saving throw.\
      \ On a failed save, a creature falls into the pit and takes 3 (d6) piercing\
      \ damage from the spikes and 3 (d6) bludgeoning damage from the fall. On a successful\
      \ save, a creature moves to the nearest unoccupied space outside that area."
    "name": "Spiky Pit Trap"
  - "desc": "The artifex chooses a point on the ground that they can see within 60\
      \ feet of them, causing a buried canister to erupt and release a 15-foot-radius,\
      \ 10-foot-high cylinder of swarming bees. When a creature enters the swarm's\
      \ area for the first time on a turn or starts their turn there, they must make\
      \ a DC 12 Constitution saving throw. On a failed save, a creature takes 5 (2d4)\
      \ poison damage and is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until\
      \ the end of their next turn. On a successful save, a creature takes half as\
      \ much damage and isn't [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned).\
      \ At the start of each of the artifex's turns, the swarm moves 10 feet away\
      \ from the artifex in a straight line. The swarm disperses after 1 minute or\
      \ when the artifex dies."
    "name": "Swarm of Bees Trap"
  - "desc": "The artifex chooses a point on the ground that they can see within 60\
      \ feet of them, igniting a concealed trench of oil and creating a 20-foot long,\
      \ 15-foot high, and 1-foot-thick wall of fire. When the wall appears, each creature\
      \ within its area must make a DC 12 Dexterity saving throw, taking 7 (2d6) fire\
      \ damage on a failed save, or half as much damage on a successful one. A creature\
      \ who enters the wall for the first time on a turn or ends their turn there\
      \ takes 7 (2d6) fire damage. The wall is opaque and lasts for 1 minute."
    "name": "Wall of Fire Trap"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/kobold-artifex-fleemortals.png"
```
^statblock
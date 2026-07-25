---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/ooze/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Blood-Borne Ooze Companion
---
# [Blood-Borne Ooze Companion](3-Mechanics\CLI\bestiary\ooze/blood-borne-ooze-companion-fleemortals.md)
*Source: Flee, Mortals! p. 311*  

```statblock
"name": "Blood-Borne Ooze Companion (FleeMortals)"
"size": "Tiny"
"type": "ooze"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "13"
  - !!int "5"
  - !!int "12"
  - !!int "8"
"speed": "30 ft."
"saves":
  - "name": "Constitution"
    "desc": "+1 plus PB"
  - "name": "Dexterity"
    "desc": "+3 plus PB"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3 plus PB"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [deafened](/3-Mechanics/CLI/conditions.md#Deafened),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 11"
"languages": ""
"traits":
  - "desc": "The ooze can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB bludgeoning damage."
    "name": "Signature Attack (Pseudopod)"
  - "desc": "The ooze makes a signature attack. On a hit, the attack deals its normal\
      \ effects, and the next attack made against the target before the start of the\
      \ ooze's next turn has advantage."
    "name": "1st Level: Distracting Attack (2 Ferocity)"
  - "desc": "The ooze takes the Hide action and makes a signature attack (in either\
      \ order). If the attack hits a Large or smaller creature, the target is knocked\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone). While the ooze is hidden in\
      \ this way, they can approach a creature or move where they're clearly visible\
      \ without automatically giving away their position."
    "name": "3rd Level: Clever Goop (5 Ferocity)"
  - "desc": "The ooze attempts to enter the body of a creature they can see within\
      \ 5 feet of them who isn't a Construct or an Undead. The target must make a\
      \ DC 10 plus PB Constitution saving throw. On a failed save, the ooze melds\
      \ into the target, who takes PBd6 necrotic damage, becomes the ooze's host,\
      \ and is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until the ooze\
      \ exits the host.\n\nWhile melded, the ooze has total cover against attacks\
      \ and other effects originating outside the host, and they can't take any action\
      \ except to exit the host as a bonus action.\n\nAt the start of each of the\
      \ ooze's turns, the host must make a DC 10 plus PB Constitution saving throw.\
      \ On a failed save, the host takes PBd6 necrotic damage and remains melded.\
      \ On a successful save, the host takes half as much damage and the ooze exits\
      \ the host. If the host dies or is subject to a cure ailment power, a protection\
      \ from poison or [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md)\
      \ spell, or a similar supernatural effect, the ooze exits the host.\n\nWhen\
      \ the ooze exits the host, they enter an unoccupied space within 5 feet of the\
      \ host."
    "name": "5th Level: Crimson Feast (8 Ferocity)"
"bonus_actions":
  - "desc": "If the ooze's caregiver is within 5 feet of them, the ooze moves inside\
      \ their caregiver. While inside their caregiver, the ooze has total cover against\
      \ attacks and other effects originating outside the caregiver. The ooze can\
      \ exit the caregiver by using another bonus action, entering an unoccupied space\
      \ within 5 feet of the caregiver."
    "name": "Parasitic Symbiosis"
  - "desc": "While inside their caregiver (see Parasitic Symbiosis), the ooze cleanses\
      \ their caregiver's blood, ending the [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ and [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) conditions on the\
      \ caregiver."
    "name": "Quick Cure (1/Day)"
"source":
  - "FleeMortals"
```
^statblock
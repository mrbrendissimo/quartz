---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Medusa
---
# [Medusa](3-Mechanics\CLI\bestiary\monstrosity/medusa-fleemortals.md)
*Source: Flee, Mortals! p. 189*  

```statblock
"name": "Medusa (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Controller"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "110"
"hit_dice": "13d8 + 52"
"modifier": !!int "5"
"stats":
  - !!int "16"
  - !!int "20"
  - !!int "18"
  - !!int "12"
  - !!int "13"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "6"
  - "dexterity": !!int "8"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+4"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common"
"cr": "6"
"actions":
  - "desc": "The medusa uses Stone Gaze and makes two attacks using Snake Bite, Heavy\
      \ Crossbow, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 10\
      \ (3d6) poison damage, and the target must succeed on a DC 15 Constitution saving\
      \ throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until the\
      \ end of the medusa's next turn."
    "name": "Snake Bite"
  - "desc": "Ranged Weapon Attack: +8 to hit, range 100/400 ft., one target. Hit:\
      \ 10 (1d10 + 5) piercing damage plus 7 (2d6) poison damage."
    "name": "Heavy Crossbow"
  - "desc": "The medusa fires energy beams from their eyes at up to three creatures\
      \ they can see within 60 feet of them. Each target must succeed on a DC 15 Constitution\
      \ saving throw or begin turning to stone (save ends at end of turn). While turning\
      \ to stone, a creature's speed is reduced by 10 feet and they have disadvantage\
      \ on Dexterity checks and saving throws.\n\nIf a creature who is turning to\
      \ stone is targeted by this action again and fails their save, their speed is\
      \ reduced by another 10 feet and they are [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the effect ends.\n\nIf a creature who is turning to stone and [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ in this way is targeted by this action again and fails their save, they are\
      \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified) and can no longer make\
      \ saving throws to end the effects of Stone Gaze. The petrification lasts until\
      \ the creature is restored by a cure ailment power of 4th order or higher, a\
      \ [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell, or a similar supernatural effect."
    "name": "Stone Gaze"
"bonus_actions":
  - "desc": "The medusa takes the Disengage or Hide action."
    "name": "Nimble Escape"
"lair_actions":
  - "desc": "When fighting inside their lair, a medusa can take lair actions. On initiative\
      \ count 20 (losing initiative ties), the medusa can take one lair action to\
      \ cause one of the following effects; the medusa can't use the same lair action\
      \ two rounds in a row:"
    "name": ""
  - "desc": "- Venom Shower. Black venom rains down in a 10-foot-radius, 40-foot-high\
      \ cylinder centered on a point the medusa can see within 90 feet of them. Each\
      \ creature in that area must succeed on a DC 15 Constitution saving throw or\
      \ be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until the end of initiative\
      \ count 20 on the next round.  \n- Shadowstep. The medusa teleports up to\
      \ 30 feet to an unoccupied space they can see.  \n- Stony Wail. The statues\
      \ in the medusa's lair scream in pain. Each enemy within 60 feet of the medusa\
      \ who can hear them must succeed on a DC 15 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the medusa until the end of initiative count 20 on the next round.  "
    "name": ""
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/medusa-fleemortals.png"
```
^statblock
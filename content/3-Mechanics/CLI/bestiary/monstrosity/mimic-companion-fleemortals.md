---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/companion
- ttrpg-cli/monster/type/monstrosity/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mimic Companion
---
# [Mimic Companion](3-Mechanics\CLI\bestiary\monstrosity/mimic-companion-fleemortals.md)
*Source: Flee, Mortals! p. 195*  

```statblock
"name": "Mimic Companion (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger, Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "5"
  - !!int "12"
  - !!int "8"
"speed": "30 ft."
"saves":
  - "name": "Dexterity"
    "desc": "+1 plus PB"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+1 plus PB"
"damage_immunities": "acid"
"condition_immunities": "[prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"traits":
  - "desc": "The mimic can use their action to polymorph into a Small, Medium, or\
      \ Large object or back into their true amorphous form. Other than size, the\
      \ mimic's statistics are the same in each form. Anything they are wearing or\
      \ carrying isn't transformed. They revert to their true form if they die."
    "name": "Shapechanger"
  - "desc": "While the mimic remains motionless, they are indistinguishable from an\
      \ ordinary object."
    "name": "False Appearance (Object Form Only)"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Bite)"
  - "desc": "The mimic makes a signature attack. On a hit, the attack deals its normal\
      \ effects, and the next attack made against the target before the start of the\
      \ mimic's next turn has advantage."
    "name": "1st Level: Distracting Attack (2 Ferocity)"
  - "desc": "The mimic attempts to adhere to each creature of their choice within\
      \ 5 feet of them. Each target must succeed on a DC 10 plus PB Dexterity saving\
      \ throw or be [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC\
      \ 10 plus PB)."
    "name": "3rd Level: Adhesive Pseudopods (5 Ferocity)"
  - "desc": "The mimic uses their Shapechanger trait to polymorph into one Large or\
      \ smaller creature they can see within 5 feet of them. Other than size, the\
      \ mimic's statistics do not change, and the mimic reverts to their previous\
      \ form at the start of their next turn.\n\nAfter transforming, the mimic can\
      \ make a signature attack against the target whose form they have taken. Hit\
      \ or miss, the target must then make a DC 10 plus PB Wisdom saving throw. On\
      \ a failed save, attacks against the target have advantage and the target has\
      \ disadvantage on attack rolls and saving throws until the start of the mimic's\
      \ next turn."
    "name": "5th Level: I'm You (8 Ferocity)"
"bonus_actions":
  - "desc": "While the mimic is within 5 feet of their caregiver, the mimic can pull\
      \ themself into the caregiver's space, cover the caregiver's body, and take\
      \ on the appearance of clothing. While the caregiver is wearing the mimic, the\
      \ mimic's space is not difficult terrain for the caregiver, the caregiver has\
      \ advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth)) checks,\
      \ and the caregiver can change the appearance of their mimic clothing at will\
      \ (no action required) as long as the caregiver and mimic aren't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated).\n\
      \nAny attack that hits the caregiver also hits the mimic they are wearing, and\
      \ vice versa, with both taking the full damage and effect of the attack. While\
      \ worn in this way, the mimic can't move, and they can't take actions other\
      \ than using a bonus action to revert to their previous form. A mimic automatically\
      \ reverts to their previous form if they enter a rampage. Upon reverting to\
      \ their previous form, the mimic is no longer worn by their caregiver, and the\
      \ mimic enters the nearest unoccupied space of their choice."
    "name": "Wearable Companion"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/mimic-companion-fleemortals.png"
```
^statblock
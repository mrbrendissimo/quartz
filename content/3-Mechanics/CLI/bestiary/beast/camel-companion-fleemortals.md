---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Camel Companion
---
# [Camel Companion](3-Mechanics\CLI\bestiary\beast/camel-companion-fleemortals.md)
*Source: Flee, Mortals! p. 46*  

```statblock
"name": "Camel Companion (FleeMortals)"
"size": "Large"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "11 plus PB (natural armor)"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "13"
  - !!int "15"
  - !!int "4"
  - !!int "12"
  - !!int "5"
"speed": "50 ft."
"saves":
  - "name": "Strength"
    "desc": "+3 plus PB"
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+1 plus PB"
"senses": "passive Perception 11"
"languages": ""
"traits":
  - "desc": "The camel is considered to be one size larger for the purpose of determining\
      \ their carrying capacity."
    "name": "Beast of Burden"
  - "desc": "The camel ignores difficult terrain created by dirt or sand. They can\
      \ tolerate temperatures as high as 120° Fahrenheit."
    "name": "Desert Dweller"
  - "desc": "The camel can go without water for up to 7 days, and without food for\
      \ up to 90 days."
    "name": "Metabolic Reserves"
  - "desc": "The camel has advantage on saving throws made to avoid or end the [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), or [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition on themself."
    "name": "Stubborn"
  - "desc": "If the camel's caregiver is Medium or smaller, the caregiver can occupy\
      \ the camel's space and vice versa, and it doesn't count as difficult terrain\
      \ for them."
    "name": "Tall and Narrow"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage (Bite) or bludgeoning damage (Kick)."
    "name": "Signature Attack (Bite or Kick)"
  - "desc": "The camel spits at a creature they can see within 10 feet of them. The\
      \ target must succeed on a DC 10 plus PB Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the start of the camel's next turn."
    "name": "1st Level: Bilious Spit (2 Ferocity)"
  - "desc": "The camel moves up to their speed and makes a signature Bite attack against\
      \ one target. If the attack hits and the target is Medium or smaller, the camel\
      \ also shakes and flings them up to 10 feet away horizontally. If the target\
      \ hits a solid surface, they are knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and take an extra PB bludgeoning damage."
    "name": "3rd Level: Punishing Shake (5 Ferocity)"
  - "desc": "The camel moves up to their speed. During this move, they can move through\
      \ other creature's spaces. Each Large or smaller creature whose space the camel\
      \ passes through must make a DC 10 plus PB Strength saving throw. On a failed\
      \ save, a creature takes PBd6 bludgeoning damage and is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ On a successful save, a creature takes half as much damage and isn't knocked\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "5th Level: Trample (8 Ferocity)"
"reactions":
  - "desc": "If the camel's caretaker falls [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and the camel can see them, the camel moves up to their speed toward their\
      \ caregiver. If they end this movement in the same space as their caregiver,\
      \ attacks against the caregiver have disadvantage until either the caregiver\
      \ is no longer [prone](/3-Mechanics/CLI/conditions.md#Prone), the caregiver\
      \ is no longer in the same space as the camel, or the start of the camel's next\
      \ turn, whichever comes first."
    "name": "Ungulate Urgency"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/camel-companion-fleemortals.png"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental/controller
- ttrpg-cli/monster/type/elemental/water
statblock: inline
statblock-link: "#^statblock"
aliases:
- Crux of Frost
---
# [Crux of Frost](3-Mechanics\CLI\bestiary\elemental/crux-of-frost-fleemortals.md)
*Source: Flee, Mortals! p. 90*  

```statblock
"name": "Crux of Frost (FleeMortals)"
"size": "Medium"
"type": "elemental"
"subtype": "water, Controller"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "135"
"hit_dice": "30d8"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "16"
  - !!int "18"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"damage_immunities": "cold, poison"
"condition_immunities": "[invisible](/3-Mechanics/CLI/conditions.md#Invisible), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Aquan, Common, plus the languages known by a creature reflected by Frosted\
  \ Reflection"
"cr": "8"
"traits":
  - "desc": "The crux can't benefit from being [invisible](/3-Mechanics/CLI/conditions.md#Invisible)."
    "name": "Scintillating"
"actions":
  - "desc": "The crux makes two Rimeglass Touch attacks, and they can use Frosted\
      \ Reflection or It Stares Back, if available."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft.,\
      \ one target. Hit: 17 (3d8 + 4) cold damage, and the target can't see or hear\
      \ creatures other than themself and the crux until the start of the crux's next\
      \ turn."
    "name": "Rimeglass Touch"
  - "desc": "The crux reflects the appearance of a specific Medium or Small creature\
      \ they've seen within the last week. This appearance is illusory and imperfect,\
      \ showing a frostbitten version of the creature. The illusion lasts until the\
      \ crux takes thunder damage, uses this action again, or is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated).\
      \ For the duration, the crux additionally knows any languages that creature\
      \ knows."
    "name": "Frosted Reflection"
  - "desc": "The crux imposes fragility on a creature within 60 feet of them who is\
      \ reflected by the crux's Frosted Reflection. If the target can see the crux,\
      \ the target must make a DC 15 Wisdom saving throw. On a failed save, the target\
      \ is [frightened](/3-Mechanics/CLI/conditions.md#Frightened) of the crux for\
      \ 1 minute (save ends at end of turn), or until the crux stops reflecting them.\
      \ While [frightened](/3-Mechanics/CLI/conditions.md#Frightened) in this way,\
      \ whenever the target takes damage, they take an extra 11 (2d10) psychic damage.\
      \ On a successful save, the target isn't [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
      \ and they are immune to the It Stares Back of all cruxes for 24 hours."
    "name": "It Stares Back (Recharge 5-6)"
"bonus_actions":
  - "desc": "The crux imbues the power of ice in themself or another Elemental they\
      \ can see within 30 feet of them, granting one of the following effects of that\
      \ Elemental's choice:\n\n- Frigid Sheen. The Elemental gains a mirror sheen\
      \ that reflects damage for 1 minute. When the Elemental is hit with an attack\
      \ by a creature they can see within 30 feet of them, the Elemental can use a\
      \ reaction to reflect the attack. The Elemental is unaffected by the attack,\
      \ and the attacker must make a DC 15 Dexterity saving throw. On a failed save,\
      \ the attack's damage and effects are reflected back at the attacker as if the\
      \ attack originated from the Elemental, turning the attacker into the target.\
      \ On a successful save, the attacker takes half as much damage, but suffers\
      \ no other effect.  \n- Frost Squall. Frost swirls around the Elemental\
      \ for 1 minute. For the duration, each non-Elemental creature who starts their\
      \ turn within 15 feet of the Elemental has their speed reduced to 15 feet unless\
      \ it is already lower until the end of their turn, and the first time they willingly\
      \ move before the start of their next turn, they take 10 (3d6) cold damage.\
      \  "
    "name": "Convocation of Ice (1/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/crux-of-frost-whereevillives.png"
```
^statblock
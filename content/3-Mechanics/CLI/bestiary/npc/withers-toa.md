---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Withers
---
# [Withers](3-Mechanics\CLI\bestiary\npc/withers-toa.md)
*Source: Tomb of Annihilation p. 145*  

Before he was turned into an undead creature, Withers was an Omuan engineer named Gorra. Like all of Omu's citizens, Gorra was enslaved and put to work constructing the tomb. When Acererak sacrificed his workers to their own dungeon, Gorra's traps performed the best.

```statblock
"name": "Withers (ToA)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "16"
  - !!int "13"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "the languages he knew in life"
"cr": "4"
"traits":
  - "desc": "Withers is a 9th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 13, +5 to hit with spell attacks). Withers has the following\
      \ wizard spells prepared:\n\nCantrips (at will): [acid splash](/3-Mechanics/CLI/spells/acid-splash-xphb.md),\
      \ [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md), [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n1st\
      \ level (4 slots): [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [expeditious retreat](/3-Mechanics/CLI/spells/expeditious-retreat-xphb.md),\
      \ [feather fall](/3-Mechanics/CLI/spells/feather-fall-xphb.md), [thunderwave](/3-Mechanics/CLI/spells/thunderwave-xphb.md)\n\
      \n2nd level (4 slots): [darkness](/3-Mechanics/CLI/spells/darkness-xphb.md),\
      \ [hold person](/3-Mechanics/CLI/spells/hold-person-xphb.md), [rope trick](/3-Mechanics/CLI/spells/rope-trick-xphb.md)\n\
      \n3rd level (3 slots): [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [lightning bolt](/3-Mechanics/CLI/spells/lightning-bolt-xphb.md)\n\n4th\
      \ level (3 slots): [blight](/3-Mechanics/CLI/spells/blight-xphb.md), [wall\
      \ of fire](/3-Mechanics/CLI/spells/wall-of-fire-xphb.md)\n\n5th level (1 slots):\
      \ [telekinesis](/3-Mechanics/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Withers carries the [amulet of the black skull](/3-Mechanics/CLI/items/amulet-of-the-black-skull-toa.md)."
    "name": "Special Equipment"
  - "desc": "While in sunlight, Withers has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Withers makes two longsword attacks. He can use his Life Drain in place\
      \ of one longsword attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 5\
      \ (1d6 + 2) necrotic damage. The target must succeed on a DC 13 Constitution\
      \ saving throw or its hit point maximum is reduced by an amount equal to the\
      \ damage taken. This reduction lasts until the target finishes a long rest.\
      \ The target dies if this effect reduces its hit point maximum to 0.\n\nA humanoid\
      \ slain by this attack rises 24 hours later as a zombie under the Withers's\
      \ control, unless the humanoid is restored to life or its body is destroyed.\
      \ Withers can have no more than twelve zombies under its control at one time."
    "name": "Life Drain"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
      \ + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands."
    "name": "Longsword"
"source":
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/withers-toa.webp"
```
^statblock
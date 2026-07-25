---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/unknown
- ttrpg-cli/monster/type/ooze/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Arcane Amalgam
---
# [Arcane Amalgam](3-Mechanics\CLI\bestiary\ooze/arcane-amalgam-fleemortals.md)
*Source: Flee, Mortals! p. 328*  

```statblock
"name": "Arcane Amalgam (FleeMortals)"
"size": "Unknown"
"type": "ooze"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"modifier": !!int "3"
"stats":
  - !!int "1"
  - !!int "16"
  - !!int "18"
  - !!int "2"
  - !!int "12"
  - !!int "2"
"speed": "20 ft., climb 20 ft., swim 20 ft."
"saves":
  - "constitution": !!int "7"
"damage_resistances": "acid, bludgeoning, piercing, slashing"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [dazed](/3-Mechanics/CLI/conditions.md#Dazed), [deafened](/3-Mechanics/CLI/conditions.md#Deafened),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), flanked, [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 120 ft. (blind beyond this radius), passive Perception 11"
"languages": ""
"cr": "6"
"traits":
  - "desc": "While in the area of an [antimagic field](/3-Mechanics/CLI/spells/antimagic-field-xphb.md)\
      \ spell, the amalgam's speed is halved and they can't use reactions. Additionally,\
      \ if targeted by the [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md)\
      \ spell, the amalgam must succeed on a Wisdom saving throw against the caster's\
      \ spell save DC or be unable to use reactions for 1 minute."
    "name": "Antimagic Lethargy"
  - "desc": "If the amalgam comes within 30 feet of a creature or object affected\
      \ by magic, the amalgam can unerringly track that target for the next 24 hours."
    "name": "Arcane Tracker"
  - "desc": "After the amalgam is hit with an attack using a mundane melee weapon,\
      \ that weapon becomes charged with vibrating energy. For the next minute, the\
      \ weapon gains a cumulative +1 bonus to damage rolls. If this bonus increases\
      \ to +3, the weapon explodes and is destroyed, and the creature wielding it\
      \ takes 10 (3d6) force damage."
    "name": "Explosive Enhancement"
  - "desc": "While the amalgam remains motionless, it is indistinguishable from a\
      \ puddle of muck."
    "name": "False Appearance"
  - "desc": "The amalgam can occupy another creature's space and vice versa, and the\
      \ amalgam can move through a space as narrow as 1 inch wide without squeezing.\
      \ The amalgam can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "The arcane amalgam makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 0 ft., one target. Hit: 14\
      \ (4d6) acid damage, or 7 (2d6) acid damage if the amalgam has half their hit\
      \ points or fewer."
    "name": "Bite"
  - "desc": "The unstable compounds that form the amalgam react violently to each\
      \ other. Each creature within 10 feet of the amalgam must make a DC 15 Dexterity\
      \ saving throw. On a failed save, a creature takes 22 (4d10) damage of a random\
      \ type (roll a d6 for each creature): 1, acid; 2, cold; 3, fire; 4, force; 5,\
      \ necrotic; 6, poison. On a successful save, a creature takes half as much damage."
    "name": "Wild Surge (Recharge 5-6)"
"reactions":
  - "desc": "When the amalgam takes damage from a spell, they emit a burst of magical\
      \ energy. Each creature within 10 feet of the amalgam must succeed on a DC 15\
      \ Dexterity saving throw or take 11 (2d10) damage of the type dealt to the amalgam\
      \ by the triggering spell. If the spell dealt more than one type of damage,\
      \ the amalgam chooses which type this reaction deals."
    "name": "Spell Reflection"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/ooze/token/arcane-amalgam-fleemortals.png"
```
^statblock
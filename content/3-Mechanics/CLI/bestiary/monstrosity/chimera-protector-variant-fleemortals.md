---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Chimera (Protector Variant)
---
# [Chimera (Protector Variant)](3-Mechanics\CLI\bestiary\monstrosity/chimera-protector-variant-fleemortals.md)
*Source: Flee, Mortals! p. 54*  

```statblock
"name": "Chimera (Protector Variant) (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Skirmisher"
"alignment": "typically  Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "119"
"hit_dice": "14d10 + 42"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "16"
  - !!int "3"
  - !!int "14"
  - !!int "11"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "understands any one language but can't speak"
"cr": "6"
"traits":
  - "desc": "When the chimera reduces a creature to 0 hit points, the chimera can\
      \ move up to their speed toward an enemy they can see."
    "name": "Volant"
  - "desc": "The chimera is divinely bound to another creature, who is their charge.\
      \ When the chimera and their charge are on the same plane, the charge can telepathically\
      \ communicate with the chimera, and the chimera knows the distance and direction\
      \ to the charge. If the chimera is within 60 feet of the charge, half of any\
      \ damage the charge takes (rounded up) is transferred to the chimera."
    "name": "Protector"
"actions":
  - "desc": "The chimera makes three Bite attacks. They can replace one attack with\
      \ a Lion's Toss attack or a use of Dragon's Eruption, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
      \ (2d6 + 4) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 9 (2d4\
      \ + 4) piercing damage, and the target must succeed on a DC 15 Strength saving\
      \ throw or be moved up to 20 feet in any direction."
    "name": "Lion's Toss"
  - "desc": "The chimera spits a volcanic explosion at a point they can see within\
      \ 120 feet of them. Each creature in a 10-foot-radius sphere centered on that\
      \ point must make a DC 14 Dexterity saving throw, taking 27 (6d8) fire damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Dragon's Eruption (Recharge 6)"
"bonus_actions":
  - "desc": "Each enemy who can hear the chimera and is within 60 feet of them must\
      \ succeed on a DC 13 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the chimera for 1 minute (save ends at end of turn). If a creature succeeds\
      \ on a saving throw against this effect or if the effect ends for them, the\
      \ creature is immune to the chimera's Roar for the next 24 hours."
    "name": "Roar"
"reactions":
  - "desc": "When a creature within 30 feet of the chimera misses them with an attack,\
      \ the chimera can move up to half their speed in a straight line toward the\
      \ creature. If the chimera ends this movement within 5 feet of the creature,\
      \ the creature must succeed on a DC 15 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Ram's Defiance"
"source":
  - "FleeMortals"
```
^statblock
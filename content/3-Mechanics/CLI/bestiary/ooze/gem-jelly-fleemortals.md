---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/ooze/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gem Jelly
---
# [Gem Jelly](3-Mechanics\CLI\bestiary\ooze/gem-jelly-fleemortals.md)
*Source: Flee, Mortals! p. 341*  

```statblock
"name": "Gem Jelly (FleeMortals)"
"size": "Large"
"type": "ooze"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "10"
"ac_class": "20 in crystalline form"
"hp": !!int "152"
"hit_dice": "16d10 + 64"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "18"
  - !!int "6"
  - !!int "14"
  - !!int "4"
"speed": "25 ft., climb 25 ft. (0 in crystalline form)"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "acid; bludgeoning, piercing, slashing from mundane attacks"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 120 ft., passive Perception 12"
"languages": ""
"cr": "9"
"traits":
  - "desc": "The gem jelly can move through a space as narrow as 1 inch wide without\
      \ squeezing."
    "name": "Amorphous"
  - "desc": "While the jelly remains motionless, they are indistinguishable from a\
      \ natural crystal formation."
    "name": "False Appearance"
"actions":
  - "desc": "The gem jelly makes two Pseudopod attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 18\
      \ (4d6 + 4) piercing damage."
    "name": "Pseudopod (True Form Only)"
  - "desc": "The jelly shatters their hardened outer layer, returning to their true\
      \ form and sending crystal shrapnel in all directions. Each creature within\
      \ 10 feet of the gem jelly must make a DC 16 Dexterity saving throw, taking\
      \ 36 (8d8) piercing damage on a failed save, or half as much damage on a successful\
      \ one. Gem jellies are immune to this damage."
    "name": "Crystalline Shatter (Crystalline Form Only)"
"bonus_actions":
  - "desc": "The gem jelly transforms into a psionically hardened crystalline form\
      \ or back into their true form. While in crystalline form, the jelly's AC increases\
      \ to 20, their speed becomes 0, they can't make Pseudopod attacks, they have\
      \ disadvantage on Dexterity saving throws, and they gain vulnerability to thunder\
      \ damage."
    "name": "Harden"
"reactions":
  - "desc": "When the jelly takes thunder damage, they use Crystalline Shatter."
    "name": "Reactive Shatter (Crystalline Form Only)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/ooze/token/gem-jelly-fleemortals.png"
```
^statblock
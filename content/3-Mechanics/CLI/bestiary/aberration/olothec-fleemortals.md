---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Olothec
---
# [Olothec](3-Mechanics\CLI\bestiary\aberration/olothec-fleemortals.md)
*Source: Flee, Mortals! p. 201*  

```statblock
"name": "Olothec (FleeMortals)"
"size": "Large"
"type": "aberration"
"subtype": "Controller"
"alignment": "typically  Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "170"
"hit_dice": "20d10 + 60"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "9"
  - !!int "16"
  - !!int "21"
  - !!int "14"
  - !!int "18"
"speed": "30 ft., fly 60 ft. (hover), swim 60 ft."
"saves":
  - "constitution": !!int "7"
  - "intelligence": !!int "9"
  - "wisdom": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+9"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+10"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 20"
"languages": "Common, Deep Speech, Undercommon, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "The olothec can breathe air and water."
    "name": "Amphibious"
  - "desc": "The olothec is immune to any power, spell, or effect that would alter\
      \ their form."
    "name": "Immutable Form"
  - "desc": "The olothec has advantage on saving throws against supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "The olothec makes six Devolving Tentacle attacks and uses Piscine Transformation."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 20 ft., one target. Hit: 12\
      \ (2d6 + 5) piercing damage. The first time a creature is hit with this attack\
      \ on a turn, they must succeed on a DC 17 Constitution saving throw or be injected\
      \ with a degenerative psionic slime (save ends at end of turn). While slimed,\
      \ each time the creature makes an attack roll or an ability check, they must\
      \ roll a d4 and subtract the number rolled from the d20 roll. At the end of\
      \ a slimed creature's turn, the size of the subtracted die increases by one:\
      \ the d4 becomes a d6, the d6 becomes a d8, and so on, to a maximum of d12.\
      \ The cure ailment power or [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md)\
      \ spell also ends this effect."
    "name": "Devolving Tentacle"
  - "desc": "The olothec targets a Humanoid they can see within 60 feet of them with\
      \ a pulse of transformational energy. The target must succeed on a DC 17 Wisdom\
      \ saving throw or undergo one of the following transformations of the olothec's\
      \ choice:\n\n- Head. The target's head transforms into the head of a fish,\
      \ proportionately sized for their body. They can't speak.  \n- Legs. The\
      \ target's legs become fins. Their walking speed is reduced to 10 feet (unless\
      \ their walking speed is slower), and they gain a swimming speed of 30 feet.\
      \  \n- Torso. The target's torso becomes the body of a fish with gills.\
      \ They can only breathe water and can hold their breath for 1 hour. If the target\
      \ isn't underwater when this transformation takes effect, they begin suffocating.\
      \  \n\nThis transformation lasts until the target is affected by a cure ailment\
      \ power of 4th order or higher or a [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell. A target who suffers all three transformations at once is permanently\
      \ transformed into a hybrid fishlike creature and can only be returned to their\
      \ original form by a [wish](/3-Mechanics/CLI/spells/wish-xphb.md) spell or similar\
      \ magic."
    "name": "Piscine Transformation (3rd-Order Power)"
"bonus_actions":
  - "desc": "The olothec teleports 30 feet to an unoccupied space they can see."
    "name": "Jaunt (3rd-Order Power)"
"source":
  - "FleeMortals"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration/artillery
statblock: inline
statblock-link: "#^statblock"
aliases:
- Overmind
---
# [Overmind](3-Mechanics\CLI\bestiary\aberration/overmind-fleemortals.md)
*Source: Flee, Mortals! p. 219*  

```statblock
"name": "Overmind (FleeMortals)"
"size": "Large"
"type": "aberration"
"subtype": "Artillery"
"alignment": "typically  Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "180"
"hit_dice": "19d10 + 76"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "18"
  - !!int "18"
  - !!int "14"
  - !!int "16"
"speed": "0 ft., fly 20 ft. (hover)"
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "6"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Common, Deep Speech, Undercommon"
"cr": "11"
"traits":
  - "desc": "Six eyes float around the overmind and create their Eye Psionics effects.\
      \ Each eye is an object that has AC 24, 1 hit point, and a psionic shield that\
      \ makes it immune to damage. After an eye creates a psionic effect, it loses\
      \ its psionic shield until the start of the overmind's next turn. If an eye\
      \ is destroyed, a new eye pops out of the overmind's face to replace it at the\
      \ end of their next turn."
    "name": "Detached Eyes"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 14\
      \ (4d6) piercing damage."
    "name": "Bite"
  - "desc": "The overmind creates three of the following psionic eye effects. Unless\
      \ otherwise stated, each eye targets a creature who the overmind can see within\
      \ 120 feet of them. They can't use the same effect twice in a turn.\n\n- 1.\
      \ Charm Beam. The targeted creature must succeed on a DC 16 Wisdom saving\
      \ throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed) by the overmind\
      \ for 1 hour, or until the overmind harms the creature or one of their allies.\
      \  \n- 2. Compulsion Beam. The targeted creature must succeed on a DC 16\
      \ Intelligence saving throw or use their reaction, if available, to move up\
      \ to their speed toward the closest ally they can see and make a weapon attack\
      \ against them. Creatures who can't be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ are unaffected.  \n- 3. Toxic Vapors. The overmind chooses a point they\
      \ can see within 120 feet of them. Each creature within 10 feet of the point\
      \ must succeed on a DC 16 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 minute (save ends at end of turn).  \n- 4. Telekinetic Beam. The\
      \ targeted creature must succeed on a DC 16 Strength saving throw or be moved\
      \ up to 30 feet in any direction and take 7 (2d6) force damage at the end of\
      \ the move. Alternatively, the overmind can target an object they can see within\
      \ 120 feet of them that weighs 300 pounds or less and isn't being worn or carried,\
      \ moving it up to 30 feet in any direction. The overmind can also exert fine\
      \ control on objects with this effect, such as manipulating a simple tool or\
      \ opening a door or a container.  \n- 5. Lightning Bolt. The overmind shoots\
      \ a 5-foot-wide, 60-foot-long line of lightning. Each creature in the line must\
      \ succeed on a DC 16 Dexterity saving throw, taking 21 (6d6) lightning damage\
      \ on a failed save, or half as much damage on a successful one.  \n- 6. Fire\
      \ Beam. The targeted creature must make a DC 16 Dexterity saving throw. On\
      \ a failed save, the target takes 36 (8d8) fire damage and catches fire, taking\
      \ 9 (2d8) fire damage at the start of each of their turns for 1 minute (save\
      \ ends at end of turn). Any creature can use their action to douse the fire,\
      \ ending the effect early.  "
    "name": "Eye Psionics"
"bonus_actions":
  - "desc": "The overmind's central eye turns solid black and projects a 150-foot\
      \ cone of energy. If the overmind or any creature in that area is affected by\
      \ a spell, the spell's effects immediately end for that creature."
    "name": "The Great Eye (Recharge 6)"
"reactions":
  - "desc": "When a creature within 5 feet of the overmind hits them with a melee\
      \ attack, the overmind can use Telekinetic Beam on the attacker."
    "name": "Away with You!"
"lair_actions":
  - "desc": "When fighting inside their lair, an overmind can take lair actions. On\
      \ initiative count 20 (losing initiative ties), the overmind can take one lair\
      \ action to cause one of the following effects; the overmind can't use the same\
      \ lair action two rounds in a row:"
    "name": ""
  - "desc": "- Gas Belch. A hole opens in the ceiling, floor, or wall at a point\
      \ the overmind chooses within 60 feet of them and belches a 20-foot-sphere of\
      \ smelly gas that lasts until the end of initiative count 20 on the next round.\
      \ When a creature enters that area for the first time or starts their turn there,\
      \ they must succeed on a DC  15 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the start of their next turn.  \n- Slime Shower. Viscous slime falls\
      \ from the ceiling toward one enemy within 120 feet of the overmind. The creature\
      \ must succeed on a DC 15 Dexterity saving throw or be vulnerable to fire and\
      \ lightning damage. The effect ends when they take fire or lightning damage,\
      \ or at the end of initiative count 20 on the next round.  \n- Telekinetic\
      \ Hold. An invisible force attempts to grab three enemies within 60 feet of\
      \ the overmind. Each creature must make a DC 15 Strength saving throw. On a\
      \ failed save, a creature's speed becomes 0 and they rise vertically 20 feet\
      \ in the air, suspended there until the end of initiative count 20 on the next\
      \ round, at which point they fall.  "
    "name": ""
"source":
  - "FleeMortals"
```
^statblock
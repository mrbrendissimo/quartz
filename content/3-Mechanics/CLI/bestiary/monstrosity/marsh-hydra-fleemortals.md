---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Marsh Hydra
---
# [Marsh Hydra](3-Mechanics\CLI\bestiary\monstrosity/marsh-hydra-fleemortals.md)
*Source: Flee, Mortals! p. 334*  

```statblock
"name": "Marsh Hydra (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "12d10 + 60"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "20"
  - !!int "3"
  - !!int "12"
  - !!int "3"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"condition_immunities": "flanked, [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": ""
"cr": "7"
"traits":
  - "desc": "The marsh hydra has advantage on saving throws against being [blinded](/3-Mechanics/CLI/conditions.md#Blinded),\
      \ [charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
      \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
      \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned), and knocked [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)."
    "name": "Multiple Heads"
  - "desc": "If the marsh hydra moves at least 20 feet straight toward a creature\
      \ and then hits them with an Entangling Serpents attack on the same turn, that\
      \ target must succeed on a DC 16 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Roll Over"
"actions":
  - "desc": "The marsh hydra makes two Entangling Serpents attacks. They can replace\
      \ one attack with a Many Bites attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14\
      \ (2d8 + 5) bludgeoning damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 16)."
    "name": "Entangling Serpents"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 9\
      \ (1d8 + 5) piercing damage, and the target must make a DC 16 Constitution saving\
      \ throw. On a failed save, the target takes 18 (4d8) poison damage and is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the end of the marsh hydra's next turn. On a successful save, the target\
      \ takes half as much damage and isn't [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)."
    "name": "Many Bites"
"bonus_actions":
  - "desc": "The marsh hydra activates one of the following effects; if the effect\
      \ targets another creature, the marsh hydra targets one creature they can see\
      \ within 30 feet of them:\n\n- 1. Poison Spit. The targeted creature must\
      \ succeed on a DC 16 Dexterity saving throw or take 9 (2d8) poison damage and\
      \ be [blinded](/3-Mechanics/CLI/conditions.md#Blinded) until the end of the\
      \ marsh hydra's next turn.  \n- 2. Entrancing Gaze. The targeted creature\
      \ must succeed on a DC 16 Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by the marsh hydra for 1 minute or until the marsh hydra harms the target\
      \ (save ends at end of turn).  \n- 3. Terrifying Rattle. The targeted creature\
      \ must succeed on a DC 16 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ by the marsh hydra for 1 minute (save ends at end of turn).  \n- 4. Reinforcements.\
      \ The marsh hydra shuffles which heads are on the outside of their body and\
      \ regains 10 (3d6) hit points.  "
    "name": "Serpent Surprise"
"source":
  - "FleeMortals"
```
^statblock
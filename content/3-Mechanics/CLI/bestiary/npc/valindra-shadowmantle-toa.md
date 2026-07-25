---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Valindra Shadowmantle
---
# [Valindra Shadowmantle](3-Mechanics\CLI\bestiary\npc/valindra-shadowmantle-toa.md)
*Source: Tomb of Annihilation p. 58*  

Liches are the remains of great wizards who embrace undeath as a means of preserving themselves. They further their own power at any cost, having no interest in the affairs of the living except where those affairs interfere with their own. Scheming and insane, they hunger for long-forgotten knowledge and the most terrible secrets. Because the shadow of death doesn't hang over them, they can conceive plans that take years, decades, or centuries to come to fruition.

A lich is a gaunt and skeletal humanoid with withered flesh stretched tight across its bones. Its eyes succumbed to decay long ago, but points of light burn in its empty sockets. It is often garbed in the moldering remains of fine clothing and jewelry worn and dulled by the passage of time.

## Biography

Valindra Shadowmantle works for Szass Tam, the most powerful lich among the Red Wizards of Thay, though she is not a Red Wizard herself. She found the heart and converted it into a base to use while her minions search for the Soulmonger. Her orders from Szass Tam are to seize control of the Soulmonger, if possible, or destroy it otherwise. Valindra created a teleportation circle inside the heart that she uses to travel instantly to and from Thay (where her phylactery is safely stored), to deliver reports to Szass Tam and pick up new instructions.

Characters who explore the Heart of Ubtao are certain to meet Valindra. She's considered the possibility that adventurers might cross her path, and she won't necessarily be hostile toward them. Her mission is to seize the Soulmonger by any means; if adventurers can help her achieve that, she'll use them.

With her ability to appear as a living elf, Valindra can easily conceal her lichdom and her association to Thay. She presents herself as a scholarly wizard who wants to "imprison" the Soulmonger; that way, its unique magic can be studied while it's safely quarantined from the world. She argues that destroying it should be a last resort.

```statblock
"name": "Valindra Shadowmantle (ToA)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "135"
"hit_dice": "18d8 + 54"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "16"
  - !!int "20"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "10"
  - "intelligence": !!int "12"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+19"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+12"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold, lightning, necrotic"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 19"
"languages": "Common, Abyssal, Draconic, Dwarvish, Elvish, Infernal"
"cr": "21"
"traits":
  - "desc": "Valindra is an 18th-level spellcaster. Her spellcasting ability is Intelligence\
      \ (spell save DC 20, +12 to hit with spell attacks). Valindra has the following\
      \ wizard spells prepared:\n\nCantrips (at will): [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md), [ray\
      \ of frost](/3-Mechanics/CLI/spells/ray-of-frost-xphb.md)\n\n1st level (4\
      \ slots): [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [magic\
      \ missile](/3-Mechanics/CLI/spells/magic-missile-xphb.md), [shield](/3-Mechanics/CLI/spells/shield-xphb.md),\
      \ [thunderwave](/3-Mechanics/CLI/spells/thunderwave-xphb.md)\n\n2nd level\
      \ (3 slots): [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [invisibility](/3-Mechanics/CLI/spells/invisibility-xphb.md), [Melf's acid\
      \ arrow](/3-Mechanics/CLI/spells/melfs-acid-arrow-xphb.md), [mirror image](/3-Mechanics/CLI/spells/mirror-image-xphb.md)\n\
      \n3rd level (3 slots): [animate dead](/3-Mechanics/CLI/spells/animate-dead-xphb.md),\
      \ [counterspell](/3-Mechanics/CLI/spells/counterspell-xphb.md), [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [fireball](/3-Mechanics/CLI/spells/fireball-xphb.md)\n\n4th level (3 slots):\
      \ [blight](/3-Mechanics/CLI/spells/blight-xphb.md), [dimension door](/3-Mechanics/CLI/spells/dimension-door-xphb.md)\n\
      \n5th level (3 slots): [cloudkill](/3-Mechanics/CLI/spells/cloudkill-xphb.md),\
      \ [scrying](/3-Mechanics/CLI/spells/scrying-xphb.md)\n\n6th level (1 slots):\
      \ [disintegrate](/3-Mechanics/CLI/spells/disintegrate-xphb.md), [globe of invulnerability](/3-Mechanics/CLI/spells/globe-of-invulnerability-xphb.md)\n\
      \n7th level (1 slots): [finger of death](/3-Mechanics/CLI/spells/finger-of-death-xphb.md),\
      \ [plane shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md)\n\n8th level\
      \ (1 slots): [dominate monster](/3-Mechanics/CLI/spells/dominate-monster-xphb.md),\
      \ [power word stun](/3-Mechanics/CLI/spells/power-word-stun-xphb.md)\n\n9th\
      \ level (1 slots): [power word kill](/3-Mechanics/CLI/spells/power-word-kill-xphb.md)"
    "name": "Spellcasting"
  - "desc": "As a bonus action, Valindra can mask her shriveled flesh and appear to\
      \ be a living elf. This magical illusion lasts until she ends it as a bonus\
      \ action or until she uses her Frightening Gaze legendary action. The effect\
      \ also ends if Valindra drops to 30 hit points or fewer, or if [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md)\
      \ is cast on her."
    "name": "Mask"
  - "desc": "When preparing her spells, Valindra can swap out any spell on her list\
      \ of prepared spells for another wizard spell of the same level."
    "name": "Preparation"
  - "desc": "If Valindra fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "If destroyed Valindra gains a new body in d10 days, regaining all her\
      \ hit points and becoming active again. The new body appears within 5 feet of\
      \ the phylactery."
    "name": "Rejuvenation"
  - "desc": "Valindra has advantage on saving throws against any effect that turns\
      \ undead."
    "name": "Turn Resistance"
"actions":
  - "desc": "Melee Spell Attack: +12 to hit, reach 5 ft., one creature. Hit: 10\
      \ (3d6) cold damage. The target must succeed on a DC 18 Constitution saving\
      \ throw or be [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed) for 1 minute.\
      \ The target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Paralyzing Touch"
"legendary_actions":
  - "desc": "Valindra casts a cantrip."
    "name": "Cantrip"
  - "desc": "Valindra uses her Paralyzing Touch."
    "name": "Paralyzing Touch (Costs 2 Actions)"
  - "desc": "Valindra fixes her gaze on one creature she can see within 10 feet of\
      \ her. The target must succeed on a DC 18 Wisdom saving throw against this magic\
      \ or become [frightened](/3-Mechanics/CLI/conditions.md#Frightened) for 1 minute.\
      \ The [frightened](/3-Mechanics/CLI/conditions.md#Frightened) target can repeat\
      \ the saving throw at the end of each of its turns, ending the effect on itself\
      \ on a success. If a target's saving throw is successful or the effect ends\
      \ for it, the target is immune to the Valindra's gaze for the next 24 hours."
    "name": "Frightening Gaze (Costs 2 Actions)"
  - "desc": "Each non-undead creature within 20 feet of Valindra must make a DC 18\
      \ Constitution saving throw against this magic, taking 21 (6d6) necrotic damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Disrupt Life (Costs 3 Actions)"
"source":
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/valindra-shadowmantle-toa.webp"
```
^statblock
---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lich
---
# [Lich](3-Mechanics\CLI\bestiary\undead/lich-fleemortals.md)
*Source: Flee, Mortals! p. 259*  

```statblock
"name": "Lich (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Controller"
"alignment": "typically  Neutral Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "270"
"hit_dice": "36d8 + 108"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "16"
  - !!int "18"
  - !!int "16"
  - !!int "20"
"speed": "30 ft., fly 50 ft. (hover)"
"saves":
  - "strength": !!int "11"
  - "constitution": !!int "10"
  - "wisdom": !!int "10"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+11"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+11"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+12"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+11"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "truesight 120 ft., passive Perception 20"
"languages": "Abyssal, Common, Draconic, Infernal"
"cr": "21"
"traits":
  - "desc": "In addition to any other spells in this stat block, the lich can cast\
      \ the following spells, using Charisma as the spellcasting ability (spell save\
      \ DC 20):\n\nAt will: [arcane lock](/3-Mechanics/CLI/spells/arcane-lock-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [disguise self](/3-Mechanics/CLI/spells/disguise-self-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [identify](/3-Mechanics/CLI/spells/identify-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [locate object](/3-Mechanics/CLI/spells/locate-object-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
      \n3/day each: [arcane eye](/3-Mechanics/CLI/spells/arcane-eye-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [arcanist's magic aura](/3-Mechanics/CLI/spells/nystuls-magic-aura-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [contact other plane](/3-Mechanics/CLI/spells/contact-other-plane-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [legend lore](/3-Mechanics/CLI/spells/legend-lore-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [scrying](/3-Mechanics/CLI/spells/scrying-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
      \n1/day each: [forbiddance](/3-Mechanics/CLI/spells/forbiddance-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [geas](/3-Mechanics/CLI/spells/geas-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [hallow](/3-Mechanics/CLI/spells/hallow-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [mirage arcane](/3-Mechanics/CLI/spells/mirage-arcane-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [symbol](/3-Mechanics/CLI/spells/symbol-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
      \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
      \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action\
      \ (see spell description) |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "If the lich is destroyed but their soulstone is intact, their soul retreats\
      \ into the stone. While the lich's soul is in the stone, a creature who can\
      \ see the stone at the start of their turn must succeed on a DC 20 Charisma\
      \ saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed) by the\
      \ stone until the end of their next turn. While [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ in this way, the creature must do everything in their power to move toward\
      \ and touch the stone, avoiding obvious hazards.\n\nIf a creature touches the\
      \ stone while the lich's soul is inside, the creature must make a DC 20 Constitution\
      \ saving throw. On a failed save, the creature drops to 0 hit points and the\
      \ lich reforms with all their hit points in an unoccupied space within 5 feet\
      \ of the soulstone. On a successful save, the creature loses half their hit\
      \ points and the lich reforms with half their hit points in an unoccupied space\
      \ within 5 feet of the soulstone.\n\nThe soulstone has AC 19, 50 hit points,\
      \ and immunity to all damage except force and thunder."
    "name": "Rejuvenation"
  - "desc": "The lich has advantage on saving throws against powers, spells, and other\
      \ supernatural effects."
    "name": "Supernatural Resistance"
  - "desc": "The lich is immune to effects that turn Undead."
    "name": "Turn Immunity"
"actions":
  - "desc": "The lich uses Glare of Undeath and makes four attacks using Biting Acid,\
      \ Disruptive Thunder, Pain of Ages, or a combination of them."
    "name": "Multiattack"
  - "desc": "Ranged Spell Attack: +12 to hit, range 120 ft., one target. Hit:\
      \ 22 (5d8) acid damage, and the target can't regain hit points until the start\
      \ of the lich's next turn."
    "name": "Biting Acid (3rd-Level Spell)"
  - "desc": "Melee  or Ranged Spell Attack: +12 to hit, reach 5 ft. or range 60\
      \ ft., one target. Hit: 22 (4d10) thunder damage. If the target is Huge or\
      \ smaller, the lich can move them up to 45 feet horizontally."
    "name": "Disruptive Thunder (3rd-Level Spell)"
  - "desc": "Melee  or Ranged Spell Attack: +12 to hit, reach 5 ft. or range 90\
      \ ft., one creature. Hit: 21 (6d6) psychic damage, and the first time the\
      \ target hits a creature with an attack before the start of the lich's next\
      \ turn, that attack deals half damage."
    "name": "Pain of Ages (3rd-Level Spell)"
  - "desc": "The lich's eyes flare with supernatural power at one creature they can\
      \ see within 60 feet of them. The target must succeed on a DC 20 Wisdom saving\
      \ throw or be compelled to hug themself tightly as protection against an unbearably\
      \ cruel world. A creature hugging themself in this way is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ for 1 minute (save ends at end of turn). A creature the target can hear and\
      \ understand can use an action to make a DC 20 Charisma ([Persuasion](/3-Mechanics/CLI/skills.md#Persuasion))\
      \ check, ending the effect on a success."
    "name": "Glare of Undeath"
  - "desc": "The lich sends negative energy coursing through a creature they can see\
      \ within 90 feet of them. The target is seared with pain and must make a DC\
      \ 20 Constitution saving throw, taking 61 (7d8 + 30) necrotic damage on a failed\
      \ save, or half as much damage on a successful one. A target reduced to 0 hit\
      \ points by this damage becomes stable but can't regain hit points, and their\
      \ spirit turns into a wraith who appears in an unoccupied space within 5 feet\
      \ of their body. This wraith acts on the lich's turn immediately after them,\
      \ and they obey the lich's verbal commands to the best of their ability. If\
      \ the wraith or lich are destroyed, the wraith disappears, the target's spirit\
      \ returns to their body, and the target can regain hit points."
    "name": "Horrid Woe (2/Day)"
  - "desc": "The lich unleashes a wave of life-sapping energy. Each enemy within 120\
      \ feet of them must make a DC 20 Constitution saving throw. On a failed save,\
      \ the target takes 16 (3d10) necrotic damage at the start of each of their turns\
      \ for 1 minute, and the lich gains temporary hit points equal to the total damage\
      \ dealt."
    "name": "Life Absorption (1/Day; 9th-Level Spell; Concentration)"
"bonus_actions":
  - "desc": "The lich enters a shadow form and moves up to their speed. While in this\
      \ form, the lich is immune to bludgeoning, piercing, and slashing damage and\
      \ the [grappled](/3-Mechanics/CLI/conditions.md#Grappled) and [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ conditions, and they can move through a space as narrow as 1 inch wide without\
      \ squeezing. The lich reverts to their true form at the end of their turn."
    "name": "Necrotic Form (3rd-Level Spell)"
"reactions":
  - "desc": "When another creature the lich can see makes an attack roll, ability\
      \ check, or saving throw, the lich can cause the roll to be made with advantage\
      \ or disadvantage."
    "name": "Immortal Insight"
"lair_actions":
  - "desc": "When fighting inside their lair, a lich can take lair actions. On initiative\
      \ count 20 (losing initiative ties), the lich can take one lair action to cause\
      \ one of the following effects; the lich can't use the same lair action two\
      \ rounds in a row:"
    "name": ""
  - "desc": "- Soul Sip. The lich chooses two enemies they can see within 90 feet\
      \ of them. Each target must succeed on a DC 20 Constitution saving throw or\
      \ take 19 (3d12) necrotic damage as the lair absorbs a sliver of their soul.\
      \  \n- Spirit Shell. The lich summons spirits to surround them until the\
      \ end of initiative count 20 of the next round. For the duration, a creature\
      \ who hits the lich with a melee attack must succeed on a DC 20 Wisdom saving\
      \ throw or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed) until the start\
      \ of the creature's next turn.  \n- Unnatural Born Leader. The lich magnifies\
      \ the power of their soulstone through the lair onto a creature they can see\
      \ within 90 feet of them. The target must succeed on a DC 20 Charisma saving\
      \ throw or use their reaction, if available, to move up to their speed and make\
      \ a weapon attack against a creature of the lich's choice.  "
    "name": ""
"source":
  - "FleeMortals"
```
^statblock
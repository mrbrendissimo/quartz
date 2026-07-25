---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Qar, Master of Jackals
---
# [Qar, Master of Jackals](3-Mechanics\CLI\bestiary\npc/qar-master-of-jackals-fleemortals.md)
*Source: Flee, Mortals! p. 365*  

```statblock
"name": "Qar, Master of Jackals (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Skirmisher"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "5"
"stats":
  - !!int "12"
  - !!int "20"
  - !!int "14"
  - !!int "13"
  - !!int "20"
  - !!int "10"
"speed": "50 ft."
"saves":
  - "strength": !!int "3"
  - "dexterity": !!int "7"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"senses": "passive Perception 17"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "If Qar is subjected to an effect that allows him to make a Dexterity\
      \ saving throw to take only half damage, he instead takes no damage if he succeeds\
      \ on the saving throw, and only half damage if he fails."
    "name": "Evasion"
  - "desc": "When Qar makes an attack, he has advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
  - "desc": "Qar has advantage on saving throws against powers, spells, and other\
      \ supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "Qar makes three Unarmed Strike attacks. If he hits the same creature\
      \ with all three attacks, the target is [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the end of their next turn."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d6\
      \ + 5) bludgeoning damage."
    "name": "Unarmed Strike"
  - "desc": "If not in the Cyst, Qar teleports to the Cyst. If in the Cyst, he teleports\
      \ to a place he has visited."
    "name": "Iron Ring (2/Day)"
"reactions":
  - "desc": "When an enemy Qar can see within 40 feet of him drops to 0 hit points,\
      \ Qar moves up to his speed. If he ends that movement within 5 feet of an enemy,\
      \ he can make an Unarmed Strike against them."
    "name": "No Survivors"
  - "desc": "When an enemy Qar can hear within 30 feet of him finishes casting a spell\
      \ with a verbal component, Qar attempts to steal their voice. The enemy must\
      \ succeed on a DC 15 Intelligence saving throw or be unable to speak for 1 minute\
      \ (save ends at end of turn)."
    "name": "Voice Stealer (3/Day)"
"source":
  - "FleeMortals"
```
^statblock
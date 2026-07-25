---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- Slarkrethel
---
# [Slarkrethel](3-Mechanics\CLI\bestiary\npc/slarkrethel-skt.md)
*Source: Storm King's Thunder p. 224*  

Beneath the waves, the kraken sleeps for untold ages, awaiting some fell sign or calling. Land-born mortals who sail the open sea forget the reasons their ancestors dreaded the ocean, even as the races of the deep ignore strange gaps in their histories when their civilizations nearly vanished after the appearance of the tentacled horror.

## Leviathans of Legend

At the beginning of time, krakens served as fierce warriors of the gods. When the gods' wars ended, the krakens shrugged free of their servitude, never again to be bound by other beings. Whole nations quake in fear when the kraken emerges from its dark demesne, and even in the middle of the deepest oceans, storms rise or abate according to its will. The kraken is a primeval force that obliterates the greatest achievements of civilization as if they were castles in the sand. Its devastating attacks can destroy ocean trade and halt communication between coastal cities.

An ominous darkness presages a kraken's attack, and a cloud of inky poison colors the water around it. Galleons and warships vanish when its tentacles uncoil from the deep, the kraken breaking their masts like kindling before drawing down ships and crew. Not even landlocked surface dwellers are safe from a kraken's wrath. Krakens can breathe air as easily as water, and some crawl up rivers to nest in freshwater lakes, destroying cities and towns along the way. Adventurers tell of these monsters lairing in the ruins of lakeside citadels, their tentacles twined around leaning towers of disintegrating stone.

## Mortal Foes

Some krakens are virtual gods, with cults and minions spread across sea and land. Others are allied with Olhydra, the evil Princess of Elemental Water, and use her cultists to enforce their will on land and sea. A kraken pleased with its worshipers can becalm rough seas and bring a bounteous harvest of fish to the faithful. However, the devious mind of a kraken is ancient beyond reckoning, and is ultimately bent to the ruination of all things.

## A Kraken's Lair

A kraken lives in dark depths, usually a sunken rift or a cavern filled with detritus, treasure, and wrecked ships.

```statblock
"name": "Slarkrethel (SKT)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "472"
"hit_dice": "27d20 + 189"
"modifier": !!int "0"
"stats":
  - !!int "30"
  - !!int "11"
  - !!int "25"
  - !!int "22"
  - !!int "18"
  - !!int "20"
"speed": "20 ft., swim 60 ft."
"saves":
  - "strength": !!int "18"
  - "dexterity": !!int "8"
  - "constitution": !!int "15"
  - "intelligence": !!int "14"
  - "wisdom": !!int "12"
"damage_immunities": "lightning; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)"
"senses": "truesight 120 ft., passive Perception 14"
"languages": "understands Abyssal, Celestial, Infernal, and Primordial but can't speak,\
  \ telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "If Slarkrethel fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Slarkrethel can breathe air and water."
    "name": "Amphibious"
  - "desc": "Slarkrethel ignores difficult terrain, and magical effects can't reduce\
      \ its speed or cause it to be [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ It can spend 5 feet of movement to escape from nonmagical restraints or being\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled)."
    "name": "Freedom of Movement"
  - "desc": "Slarkrethel deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "Slarkrethel makes three tentacle attacks, each of which it can replace\
      \ with one use of Fling."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +17 to hit, reach 5 ft., one target. Hit: 23\
      \ (3d8 + 10) piercing damage. If the target is a Large or smaller creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by Slarkrethel, that creature is swallowed, and the grapple ends. While swallowed,\
      \ the creature is [blinded](/3-Mechanics/CLI/conditions.md#Blinded) and [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ it has total cover against attacks and other effects outside Slarkrethel,\
      \ and it takes 42 (12d6) acid damage at the start of each of Slarkrethel's turns.\
      \ If Slarkrethel takes 50 damage or more on a single turn from a creature inside\
      \ it, Slarkrethel must succeed on a DC 25 Constitution saving throw at the end\
      \ of that turn or regurgitate all swallowed creatures, which fall [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ in a space within 10 feet of Slarkrethel. If Slarkrethel dies, a swallowed\
      \ creature is no longer [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by it and can escape from the corpse using 15 feet of movement, exiting [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +17 to hit, reach 30 ft., one target. Hit: 20\
      \ (3d6 + 10) bludgeoning damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 18). Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ Slarkrethel has ten tentacles, each of which can grapple one target."
    "name": "Tentacle"
  - "desc": "One Large or smaller object held or creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by Slarkrethel is thrown up to 60 feet in a random direction and knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ If a thrown target strikes a solid surface, the target takes 3 (d6) bludgeoning\
      \ damage for every 10 feet it was thrown. If the target is thrown at another\
      \ creature, that creature must succeed on a DC 18 Dexterity saving throw or\
      \ take the same damage and be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Fling"
  - "desc": "Slarkrethel magically creates three bolts of lightning, each of which\
      \ can strike a target Slarkrethel can see within 120 feet of it. A target must\
      \ make a DC 23 Dexterity saving throw, taking 22 (4d10) lightning damage on\
      \ a failed save, or half as much damage on a successful one."
    "name": "Lightning Storm"
  - "desc": "Slarkrethel casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 22):\n\n\
      At will: [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [detect\
      \ thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [sending](/3-Mechanics/CLI/spells/sending-xphb.md)\n\
      \n2/day each: [control weather](/3-Mechanics/CLI/spells/control-weather-xphb.md)\
      \ (cast as 1 action), [fly](/3-Mechanics/CLI/spells/fly-xphb.md), [ice storm](/3-Mechanics/CLI/spells/ice-storm-xphb.md)\n\
      \n1/day each: [arcane eye](/3-Mechanics/CLI/spells/arcane-eye-xphb.md),\
      \ [chain lightning](/3-Mechanics/CLI/spells/chain-lightning-xphb.md), [feeblemind](/3-Mechanics/CLI/spells/befuddlement-xphb.md),\
      \ [foresight](/3-Mechanics/CLI/spells/foresight-xphb.md), [locate creature](/3-Mechanics/CLI/spells/locate-creature-xphb.md),\
      \ [mass suggestion](/3-Mechanics/CLI/spells/mass-suggestion-xphb.md), [nondetection](/3-Mechanics/CLI/spells/nondetection-xphb.md),\
      \ [power word kill](/3-Mechanics/CLI/spells/power-word-kill-xphb.md), [scrying](/3-Mechanics/CLI/spells/scrying-xphb.md)\
      \ (cast as 1 action), [sequester](/3-Mechanics/CLI/spells/sequester-xphb.md),\
      \ [telekinesis](/3-Mechanics/CLI/spells/telekinesis-xphb.md), [teleport](/3-Mechanics/CLI/spells/teleport-xphb.md)"
    "name": "Spellcasting"
"legendary_actions":
  - "desc": "Slarkrethel makes one tentacle attack or uses its Fling."
    "name": "Tentacle Attack or Fling"
  - "desc": "Slarkrethel uses Lightning Storm."
    "name": "Lightning Storm (Costs 2 Actions)"
  - "desc": "While underwater, Slarkrethel expels an ink cloud in a 60-foot radius.\
      \ The cloud spreads around corners, and that area is heavily obscured to creatures\
      \ other than Slarkrethel. Each creature other than Slarkrethel that ends its\
      \ turn there must succeed on a DC 23 Constitution saving throw, taking 16 (3d10)\
      \ poison damage on a failed save, or half as much damage on a successful one.\
      \ A strong current disperses the cloud, which otherwise disappears at the end\
      \ of Slarkrethel's next turn."
    "name": "Ink Cloud (Costs 3 Actions)"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), the kraken takes a lair\
      \ action to cause one of the following magical effects:"
    "name": ""
  - "desc": "- A strong current moves through the kraken's lair. Each creature within\
      \ 60 feet of the kraken must succeed on a DC 23 Strength saving throw or be\
      \ pushed up to 60 feet away from the kraken. On a success, the creature is pushed\
      \ 10 feet away from the kraken.  \n- Creatures in the water within 60 feet of\
      \ the kraken have vulnerability to lightning damage until initiative count 20\
      \ on the next round.  \n- The water in the kraken's lair becomes electrically\
      \ charged. All creatures within 120 feet of the kraken must succeed on a DC\
      \ 23 Constitution saving throw, taking 10 (3d6) lightning damage on a failed\
      \ save, or half as much damage on a successful one.  "
    "name": ""
"regional_effects":
  - "desc": "The region containing a kraken's lair is warped by the creature's blasphemous\
      \ presence, creating the following magical effects:"
    "name": ""
  - "desc": "- The kraken can alter the weather at will in a 6-mile radius centered\
      \ on its lair. The effect is identical to the [control weather](/3-Mechanics/CLI/spells/control-weather-xphb.md)\
      \ spell.  \n- Water elementals coalesce within 6 miles of the lair. These elementals\
      \ can't leave the water and have Intelligence and Charisma scores of 1 (-5).\
      \  \n- Aquatic creatures within 6 miles of the lair that have an Intelligence\
      \ score of 2 or lower are [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by the kraken and aggressive toward intruders in the area.  "
    "name": ""
  - "desc": "When the kraken dies, all of these regional effects fade immediately."
    "name": ""
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/slarkrethel-skt.webp"
```
^statblock
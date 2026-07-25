---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Uthgardt Shaman
---
# [Uthgardt Shaman](3-Mechanics\CLI\bestiary\humanoid/uthgardt-shaman-skt.md)
*Source: Storm King's Thunder p. 243*  

The Uthgardt are suspicious and resentful of most kinds of magic. Seldom do they choose to become shamans. Instead, the role is thrust upon those who are born with a strong connection to the spirit world. To be a shaman is to stand with one foot in the land of the living and the other in the land of the dead. Those who walk the shadowed path between two lands do so because the spirits of the dead compel them. Other Uthgardt fear and respect a shaman's power.

An Uthgardt shaman must possess a sacred bundle to cast spells. A sacred bundle is made up of sticks, bones, feathers, tufts of fur, and stones that have been "touched" by spirits. It takes a month for a shaman to assemble a sacred bundle, and a shaman can use only one such bundle at a time. A sacred bundle benefits only the shaman who created it, and it doesn't replace the normal components of a spell.

In addition to the spells that all Uthgardt shamans can cast, a shaman of a particular tribe gains additional spells based on tribal affiliation (see the "Uthgardt Sha man Tribal Spells" sidebar).

By communing with their ancestors' spirits, Uthgardt shamans can also learn secret rituals. These rituals almost always require some sort of blood sacrifice, and their effects are usually transformative. For example, some Black Raven shamans know a ritual that allows them to hatch giant ravens from normal raven eggs, and some shamans of the Griffon tribe can transform them selves into griffons by performing a ritual that requires them to drink copious amounts of horse blood.

## Uthgardt Shaman Tribal Spells

Depending on an Uthgardt shaman's tribe, the shaman's Innate Spellcasting feature gains additional spells the shaman can cast once per day.

Black Lion: [chill touch](/3-Mechanics/CLI/spells/chill-touch-xphb.md), [feign death](/3-Mechanics/CLI/spells/feign-death-xphb.md), [revivify](/3-Mechanics/CLI/spells/revivify-xphb.md)

Black Raven: [animal messenger](/3-Mechanics/CLI/spells/animal-messenger-xphb.md) (raven only), [polymorph](/3-Mechanics/CLI/spells/polymorph-xphb.md) (self only; into a raven only)

Blue Bear: [enhance ability](/3-Mechanics/CLI/spells/enhance-ability-xphb.md) (bear's endurance only), [heroism](/3-Mechanics/CLI/spells/heroism-xphb.md)

Elk: [find steed](/3-Mechanics/CLI/spells/find-steed-xphb.md) (cast as 1 action; elk only), [haste](/3-Mechanics/CLI/spells/haste-xphb.md)

Gray Wolf: [beast sense](/3-Mechanics/CLI/spells/beast-sense-xphb.md) (wolf or dire wolf only), [moonbeam](/3-Mechanics/CLI/spells/moonbeam-xphb.md), [speak with animals](/3-Mechanics/CLI/spells/speak-with-animals-xphb.md) (wolf or dire wolf only)

Great Worm: [crusader's mantle](/3-Mechanics/CLI/spells/crusaders-mantle-xphb.md), [hypnotic pattern](/3-Mechanics/CLI/spells/hypnotic-pattern-xphb.md)

Griffon: [beast sense](/3-Mechanics/CLI/spells/beast-sense-xphb.md) (birds only), [fly](/3-Mechanics/CLI/spells/fly-xphb.md)

Sky Pony: [gust of wind](/3-Mechanics/CLI/spells/gust-of-wind-xphb.md), [witch bolt](/3-Mechanics/CLI/spells/witch-bolt-xphb.md)

Red Tiger: [enhance ability](/3-Mechanics/CLI/spells/enhance-ability-xphb.md) (cat's grace only), [jump](/3-Mechanics/CLI/spells/jump-xphb.md)

Thunderbeast: [enhance ability](/3-Mechanics/CLI/spells/enhance-ability-xphb.md) (bull's strength only), [pass without trace](/3-Mechanics/CLI/spells/pass-without-trace-xphb.md)

Tree Ghost: [barkskin](/3-Mechanics/CLI/spells/barkskin-xphb.md), [speak with plants](/3-Mechanics/CLI/spells/speak-with-plants-xphb.md)

```statblock
"name": "Uthgardt Shaman (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "13"
  - !!int "10"
  - !!int "15"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+6"
"senses": "passive Perception 14"
"languages": "Bothii, Common"
"cr": "2"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
      \ damage if wielded with two hands."
    "name": "Spear"
  - "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
      \ 4 (1d6 + 1) piercing damage."
    "name": "Shortbow"
  - "desc": "The shaman casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 12; +4 to hit with spell attacks):\n\nAt will:\
      \ [dancing lights](/3-Mechanics/CLI/spells/dancing-lights-xphb.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [message](/3-Mechanics/CLI/spells/message-xphb.md), [thaumaturgy](/3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\
      \n1/day each: [augury](/3-Mechanics/CLI/spells/augury-xphb.md) (cast as\
      \ 1 action), [bestow curse](/3-Mechanics/CLI/spells/bestow-curse-xphb.md), [cordon\
      \ of arrows](/3-Mechanics/CLI/spells/cordon-of-arrows-xphb.md), [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [speak with dead](/3-Mechanics/CLI/spells/speak-with-dead-xphb.md), [spirit\
      \ guardians](/3-Mechanics/CLI/spells/spirit-guardians-xphb.md)"
    "name": "Spellcasting (Requires a Sacred Bundle)"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/uthgardt-shaman-skt.webp"
```
^statblock
---
tags:
  - Category/Group
MyContainer: "[[2-World/Regions/Faerûn.md|Faerûn]]"
MyCategory: Knightly Order
obsidianUIMode: preview
leader: Bob
officers:
  - Officer 1
  - Officer 2
members:
  - Member 1
  - Member 2
  - Member 3
  - Zindra Winterbow
initiates:
  - Miros Xelbrin
faction: Faction Name 1
primary_contact: John Doe
benefits:
  - standing: 1
    reward: What do they get at level 1?
  - standing: 2
    reward: What do they get at level 2?
  - standing: 3
    reward: What do they get at level 3?
aliases:
  - The Emerald Enclave
---






%% DO NOT MAKE CHANGES TO THIS PART OF THE TEMPLATE %%

> [!NOTE] Parent Region: `INPUT[suggester(optionQuery(#Category/Place)):MyContainer]`

> [!column|no-i no-t]
>> [!note|no-title]
>> ![[emblem_emerald-enclave.jpg|400]]
>
>> [!note|div-m] Place Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️General),
>> option(2, ⁉️Goals),
>> option(3, 📝GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!note|no-title]
>>> > ![[#General|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#Goals|no-h clean]]
>>> 
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 

%% DO NOT MAKE CHANGES TO THIS PART OF THE TEMPLATE %%

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, 🔗Hierarchy),
> option(2, ⚡Enemies/Allies),
> option(3, 🛠️Services),
> option(4,➕Membership),
> option(5, 🛡️Ranks),
> class(tabbed)
> )]
> ~~~
> >[!tabbed-box-maxh]
> > >[!div-m|no-title]
> > > ![[#Hierarchy|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Enemies/Allies|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Services|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Membership|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Ranks|no-h clean]]

%% MAKE CHANGES BELOW THIS LINE %%

---

# General

**Select Parent:** `INPUT[suggester(optionQuery(#Category/Hub),optionQuery(#Category/Region)):MyContainer]`

**Select Category:** `INPUT[inlineSelect(option(Knightly Order), option(Religious Order), option(Magic Academy), option(Artisan Guild), option(Merchant Consortium), option(Criminal Syndicate), option(Mercenary Company), option(Noble House), option(Secret Society or Cult), option(Adventurers’ Guild)):MyCategory]`

**Values:**
- The natural order must be respected and preserved.
- Forces that upset the natural order must be destroyed.
- Civilization and the wilderness must learn to coexist peacefully.

**Allies:**
Church of Eldath
Church of Mielikki
Church of Nobanion
Church of Silvanus

**Enemies:**
Church of Bane
Church of Talos
Church of Malar
People of the Black Blood
Red Wizards of Thay
Zhentarim

Membership Requirements:

# Goals
- Restore and preserve the natural order.
- Destroy all that is unnatural.
- Keep the elemental forces of the world in check.
- Keep civilization and the wilderness from destroying each other.
-
> [!NOTE]- Private Goals
> - [ ] Achieve This
> - [ ] Achieve That

# Membership
To join the group, a PC must spend X week 'doing' something, or 'something else'.

# GM Notes

The Emerald Enclave is a widespread group of wilderness survivalists who preserve the natural order while rooting out unnatural threats. The organization is decentralized, hardy, and reclusive. Barbarians, druids, and rangers of good or neutral alignments are commonly drawn to the Emerald Enclave.

# Hierarchy

`BUTTON[button_person]` List important relationships here. 

```dataviewjs
// 1) Grab your frontmatter arrays
const leader    = dv.current().leader    ?? null;
const officers  = dv.current().officers  ?? [];
const members   = dv.current().members   ?? [];
const initiates = dv.current().initiates ?? [];

// 2) Render the Mermaid diagram
dv.paragraph(
  "```mermaid\nflowchart LR\n" +

  // Leader node
  (leader
    ? `L[${leader}]:::internal-link\n`
    : "") +

  // Officers group
  (officers.length > 0
    ? `OG[Officers]\nL --> OG\n` +
      officers.map((o,i) =>
        `O${i+1}[${o}]:::internal-link\nOG --> O${i+1}\n`
      ).join("")
    : "") +

  // Members group
  (members.length > 0
    ? `MG[Members]\n${officers.length ? "OG" : "L"} --> MG\n` +
      members.map((m,i) =>
        `M${i+1}[${m}]:::internal-link\nMG --> M${i+1}\n`
      ).join("")
    : "") +

  // Initiates group
  (initiates.length > 0
    ? `IG[Initiates]\n${members.length ? "MG" : (officers.length ? "OG" : "L")} --> IG\n` +
      initiates.map((n,i) =>
        `I${i+1}[${n}]:::internal-link\nIG --> I${i+1}\n`
      ).join("")
    : "") +

  "```"
)
```

> [!NOTE]- Relationship Config - Enter name of People Notes
> | Leader    | Officers    | 
> | --- | --- | 
> | `INPUT[list:leader]`    | `INPUT[list:officers]`    | 
> 
> | Members    | Initiates    | 
> | --- | --- | 
> | `INPUT[list:members]`    | `INPUT[list:initiates]`    |

# Enemies/Allies
**Enemies:** `INPUT[inlineListSuggester(optionQuery(#Category/Group),optionQuery(#Category/People)):MyEnemies]`

**Allies:** `INPUT[inlineListSuggester(optionQuery(#Category/Group),optionQuery(#Category/People)):MyAllies]`

# People

The following people are members of this group.  

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender"
FROM "2-Campaign/Quests"
WHERE contains(Connected_Groups, this.file.link)
SORT file.name ASC
```


```base
properties:
  property.char_age:
    displayName: Age
  property.char_gender:
    displayName: Gender
  property.char_race:
    displayName: Race
  property.char_status:
    displayName: Status
  file.name:
    displayName: Name
  note.char_status:
    displayName: Status
  note.char_race:
    displayName: Race
  note.char_gender:
    displayName: Gender
  note.char_age:
    displayName: Age Range
views:
  - type: table
    name: People
    filters:
      and:
        - file.inFolder("2-World/People")
        - MyContainer.contains(this.file.path)
    order:
      - file.name
      - MyContainer
      - MyCategory
      - char_status
      - char_race
      - char_gender
      - char_age
    sort:
      - column: note.char_race
        direction: ASC
      - column: note.MyContainer
        direction: ASC
      - column: file.name
        direction: ASC
    columnSize:
      file.name: 177
      note.MyCategory: 221
      note.MyContainer: 244
      note.char_status: 137
      note.char_race: 160
      note.char_gender: 143
      note.char_age: 149

```


# Services

Services offered. 


> [!NOTE]+ Public Services
> | Item   | Cost | Weight |
> | ------ | ---- | ------ |
> | Service 1 | 1gp  | L      |
> | Service 2 | 1cp  | -      |

> [!NOTE]- Member Services
> | Item   | Cost | Weight |
> | ------ | ---- | ------ |
> | Service 1 | 1gp  | L      |
> | Service 2 | 1cp  | -      |

# Ranks

Members of the Emerald Enclave usually operate in isolation, relying on their own instincts and abilities to survive. Some, however, engage with the people of the world as protectors, emerging from the wilderness to help others survive its perils. At times, all are called together to combat foes great enough to disrupt the natural order of the land.

The Emerald Enclave comprises mostly druids and rangers, but welcome all with a strong tie to nature and a willingness to live with the land.

- Springwarden (1 Renown)
- Summerstrider (3 Renown)
- Autumnreaver (10 Renown)
- Winterstalker (25 Renown)
- Master of the Wild (50 Renown)
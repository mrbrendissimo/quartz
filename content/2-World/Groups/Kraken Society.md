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
initiates:
  - Initiative 1
  - Initiative 2
  - Initiative 3
faction: Faction Name 1
primary_contact: John Doe
benefits:
  - standing: 1
    reward: What do they get at level 1?
  - standing: 2
    reward: What do they get at level 2?
  - standing: 3
    reward: What do they get at level 3?
---






%% DO NOT MAKE CHANGES TO THIS PART OF THE TEMPLATE %%

> [!NOTE] Parent Region: `INPUT[suggester(optionQuery(#Category/Place)):MyContainer]`

> [!column|no-i no-t]
>> [!note|no-title]
>> ![[emblem_Kraken_Society.webp|500]]
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

The Kraken Society is a secret group of spies, smugglers, slavers, and assassins. It is rumoured that the founder of their organization is [Slarkrethel](https://www.worldanvil.com/w/the-azure-sea-merecraft/a/slarkrethel-person), the magic-using kraken that lives in the depths of [The Azure Sea](https://www.worldanvil.com/w/the-azure-sea-merecraft/a/the-azure-sea-location).   For thousands of years, the Kraken Society has been searching tirelessly for a long-lost path to divine ascendancy for it's earthbound ruler. In the meantime, its stretches its tentacles across [The Known World](https://www.worldanvil.com/w/the-azure-sea-merecraft/a/the-known-world-location), laying low powers that might one day threaten it.   The calling card of the Kraken Society, a purple squid with an incredible number of tentacles, is synonymous with kidnappings, torture, assassinations, and brute force.   Whilst those few who know of their existence often think of the Society as yet another organization that is a gatherer of information (some even refer to its members as the _Heralds of the Sea_), there has always been something sinister in their dealings; an eerie sense of danger and intrigue in their mannerisms.   On the mainland the Society is said to have spies who lurk in the shadows of cities and towns, gathering information for [Slarkrethel](https://www.worldanvil.com/w/the-azure-sea-merecraft/a/slarkrethel-person), and partaking in dark rituals to further his power. Many of these spies lead double lives and occupy high stations within major cities around [The Azure Sea](https://www.worldanvil.com/w/the-azure-sea-merecraft/a/the-azure-sea-location).

# Goals

> [!NOTE]+ Public Goals
> - [ ] Achieve This
> - [ ] Achieve That

> [!NOTE]- Private Goals
> - [ ] Achieve This
> - [ ] Achieve That

# Membership
To join the group, a PC must spend X week 'doing' something, or 'something else'.

# GM Notes

Make notes of what you need to track in the town here. 

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

Ranks listed here

- Rank 1: Benefit
- Rank 2: Benefit
- Rank 3: Benefit

---
MyContainer:
  - "[[2-World/Hubs/Goldenfields.md|Goldenfields]]"
  - "[[G6. Town|G6. Town]]"
MyCategory:
tags:
  - Category/People
obsidianUIMode: preview
aliases:
  - characters other name
NoteStatus: ❓
char_status: Alive
char_race: Human
char_gender: Male
char_items:
char_age: Adult
parents:
  - Josh
  - Susan
children:
  - Bob
  - Fred
enemies:
  - Zander
allies:
  - Emyerson
  - Bob
  - Frank
siblings:
  - Flip
partner:
  - Jane
Connected_Quests:
  - "[[2-World/Quests/Goldenfields/Lifferlas’s Quest.md|Lifferlas’s Quest]]"
Connected_Groups: "[[z_Templates/World Builder Templates/Template-Group.md|Template-Group]]"
---




> [!NOTE|div-m] Parent Location: `INPUT[inlineListSuggester(optionQuery(#Category/Hub),optionQuery(#Category/Region),optionQuery(#Category/Place),optionQuery(#Category/PointofInterest)):MyContainer]`

> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[lifferlas.webp]]
>
>> [!div-m|no-title] Place Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️General),
>> option(2, 📒Statblock),
>> option(3, 📝GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#General|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#Statblock|no-h clean]]
>>> 
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, ⚔️Inventory),
> option(2, 🔗Connections),
> option(3, 🧑‍🤝‍🧑Relationships),
> class(tabbed)
> )]
> ~~~
> >[!tabbed-box-maxh]
> > >[!div-m|no-title]
> > > ![[#Inventory|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Connections|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Relationships|no-h clean]]

---

# General

Name: `= this.file.name`

Status: `INPUT[inlineSelect(option(Alive), option(Dead)):char_status]`

Race/Species: `INPUT[template-Race][:char_race]`

%% The options in the drop-down above are controlled via the Meta Bind Input Field Templates in the Settings %%

Gender: `INPUT[inlineSelect(option(Male), option(Female), option(Other)):char_gender]` 

Age: `INPUT[inlineSelect(option(Infant), option(Child), option(Teenager), option(Young Adult), option(Adult), option(Elder)):char_age]`

---

An awakened tree. Created by a long-dead druid, Lifferlas is the oldest living resident of Goldenfields. It speaks Common and has long entertained the children of the workers with harrowing, often humorous tales of heroes and monsters, as well as legends about the gods, Chauntea in particular. The tree allows children to climb it while it walks about cautiously with hosts of them clinging to its boughs and screaming with delight.

A druid of the Emerald Enclave awakened the tree Lifferlas with a spell. Goldenfields is his home, its people his friends. Children like to carve their names and initials into his body and hang from his boughs, and he’s happy with that.

**Ideal:** “I exist to protect the people and plants of Goldenfields.”

**Bond:** “Children are wonderful. I would do anything to make them feel happy and safe.”

**Flaw:** “I can’t remember people’s names and often get them mixed up.”

# Statblock

```statblock
monster: Lifferlas (SKT)
```

# GM Notes

Make notes of what you need to track in the town here. 

# Inventory

The following items belong to `= this.file.name`.

```dataviewjs
// 1. grab all pages in the folder
let pages = dv.pages('"3-Mechanics/Items"').values;

// 2. shuffle (Fisher–Yates)
for (let i = pages.length - 1; i > 0; i--) {
  const j = Math.floor(Math.random() * (i + 1));
  [pages[i], pages[j]] = [pages[j], pages[i]];
}

// 3. take the first two
let pick = pages.slice(0, 1);

// 4. render table of clickable links + Gender
dv.table(
  ["Random Item", "cost", "weight"],
  pick.map(p => [
    dv.fileLink(p.file.path),        // clickable note link
    p.cost ?? "—",                  // frontmatter field (falls back to “—” if missing)
    p.weight ?? "—"                  // frontmatter field (falls back to “—” if missing)
  ])
);
```

# Connections
Is the person linked to any groups or quests?

Quests: `INPUT[inlineListSuggester(optionQuery(#Category/Quest)):Connected_Quests]`

Groups: `INPUT[inlineListSuggester(optionQuery(#Category/Group)):Connected_Groups]`

# Relationships

List important relationships here. 

```dataviewjs
var parents = dv.current().parents ?? [];
var children = dv.current().children ?? [];
var enemies = dv.current().enemies ?? [];
var allies = dv.current().allies ?? [];
var siblings = dv.current().siblings ?? [];
var current = dv.current().file.name;
var partner = dv.current().partner ?? [];

dv.paragraph("```mermaid\nflowchart LR\n" +
  // Parents with internal-link on individual nodes only
  (parents.length > 0 ? parents.map((parent, index) => `P${index + 1}[${parent}]:::internal-link\nP${index + 1} --> Current\n`).join('') : '') +
  
  // Current node
  `Current[${current}]\n` +
  
  // Partner group node (no internal-link applied)
  (partner.length > 0 ? `PT[Partner]\nCurrent --> PT\n` : '') +
  
  // Individual partners with internal-link
  (partner.length > 0 ? partner.map((p, index) => `PT${index + 1}[${p}]:::internal-link\nPT --> PT${index + 1}\n`).join('') : '') +

  // Children group node (no internal-link applied)
  (children.length > 0 ? `C[Children]\nCurrent --> C\n${children.map((child, index) => `C${index + 1}[${child}]:::internal-link\nC --> C${index + 1}\n`).join('')}` : '') +

  // Siblings group node (no internal-link applied)
  (siblings.length > 0 ? `S[Siblings]\nCurrent --> S\n${siblings.map((sibling, index) => `S${index + 1}[${sibling}]:::internal-link\nS --> S${index + 1}\n`).join('')}` : '') +

  // Enemies group node (no internal-link applied)
  (enemies.length > 0 ? `E[Enemies]\nCurrent --> E\n${enemies.map((enemy, index) => `E${index + 1}[${enemy}]:::internal-link\nE --> E${index + 1}\n`).join('')}` : '') +

  // Allies group node (no internal-link applied)
  (allies.length > 0 ? `A[Allies]\nCurrent --> A\n${allies.map((ally, index) => `A${index + 1}[${ally}]:::internal-link\nA --> A${index + 1}\n`).join('')}` : '') +

  // Styling: Apply internal-link only to individual nodes, not group nodes
  `class ${parents.length > 0 ? parents.map((_, index) => `P${index + 1},`).join('') : ''}Current${children.length > 0 ? children.map((_, index) => `C${index + 1},`).join('') : ''}${siblings.length > 0 ? siblings.map((_, index) => `S${index + 1},`).join('') : ''}${enemies.length > 0 ? enemies.map((_, index) => `E${index + 1},`).join('') : ''}${allies.length > 0 ? allies.map((_, index) => `A${index + 1},`).join('') : ''} internal-link;`
)
```

> [!NOTE]- Relationship Config - Enter name of People Notes
> `BUTTON[button_person]` Nodes will link to notes of the same name. 
> 
> | Parents    | Partner    | Children |
> | --- | --- | --- |
> | `INPUT[list:parents]`    | `INPUT[list:partner]`    | `INPUT[list:children]`  |
> 
> | Siblings    | Enemies    | Allies |
> | --- | --- | --- |
> | `INPUT[list:siblings]`    | `INPUT[list:enemies]`    | `INPUT[list:allies]`  |




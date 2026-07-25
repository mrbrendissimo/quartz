---
tags:
  - Category/Hub
container: Test
MyContainer: "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
MyCategory: City +1500
obsidianUIMode: preview
mapCalc1: NaN
map_height_y: 1200
map_width_x: 1684
---

> [!NOTE]- Quick Calculator  
> Map Height in Pixels: `INPUT[number:map_height_y]`  
> Map Width in Pixels: `INPUT[number:map_width_x]`  
> lat: `VIEW[{map_height_y} / 2][math]`  
> long: `VIEW[{map_width_x} / 2][math]`  
> How Many Pixels In Scale: `INPUT[number:scale_pixels]`  
> How Many Units in Scale: `INPUT[number:scale_pixels_range]`  
> Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`


> [!NOTE|div-m] Parent Region: `INPUT[suggester(optionQuery(#Category/Region)):MyContainer]`

> [!column|no-i no-t]
>> [!info|no-title] Map
>> ```leaflet  
>> id: tm_Bryn-Shander ### Must be unique with no spaces  
>> image: [[tm_Bryn-Shander.webp]] ### Link to the map image file. Do not add a ! in front of the image  
>> bounds: [[0,0], [1200, 1684]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
>> height: 500px ### Size of the leaflet embed in px on your screen  
>> width: 95% ### Size of the leaflet embed in your note  
>> lat: 600 ### To center the map, make this half of the map height.  
>> long: 842 ### To center the map, make this half of the map width.  
>> minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
>> maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
>> defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
>> zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
>> unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
>> scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
>> recenter: false  
>> darkmode: false ### marker
>> ```
>
>> [!note|no-title] Town Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️General),
>> option(2, 🏃‍♂️‍➡️NPCs),
>> option(3, 📝GM Notes),
>> option(4, 🐎Travel),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#General|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#NPCs|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 
>>> > [!div-m|no-title]
>>> > ![[#Travel|no-h clean]]
>>> 

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, 🛒Commerce),
> option(2, 🍎Agriculture),
> option(3, ⚔️Military),
> option(4, 💭Philosophy),
> option(5, ⚙️Industrial),
> option(6, 🏠Nesting),
> option(7, 👑Government),
> class(tabbed)
> )]
> ~~~
> >[!tabbed-box-maxh]
> > >[!div-m|no-title]
> > > ![[#Commerce|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Agriculture|no-h2 clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Military|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Philosophy|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Industrial|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Nesting|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Government|no-h clean]]

---
# General

Select Settlement: `INPUT[suggester(optionQuery(#Category/Region)):MyContainer]`

Select Category: `INPUT[inlineSelect(option(City +1500), option(Town +200), option(Village +80), option(Hamlet <80), option(Encampment), option(Keep), option(Fortress), option(Stronghold)):MyCategory]`


# NPCs

`BUTTON[button_person]` List important NPCs here. 

```dataviewjs
// 1) Hub’s vault-relative path
const hubPath = dv.current().file.path;

// 2) Helper to extract the path from a "[[path|alias]]" entry
function extractPaths(mc) {
  if (!mc) return [];
  const arr = Array.isArray(mc) ? mc : [mc];
  return arr
    .map(link => {
      const m = String(link).match(/\[\[(.*?)\|/);
      return m ? m[1] : null;
    })
    .filter(Boolean);
}

// 3) Find all Places whose MyContainer points to this Hub
const placePages = dv.pages(`"2-World/Places"`)
  .where(p => extractPaths(p.MyContainer).includes(hubPath))
  .values;
// collect their **paths**
const placePaths = placePages.map(p => p.file.path);

// 4a) Indirect People: whose MyContainer links to any of those placePaths
const indirect = dv.pages(`"2-World/People"`)
  .where(p => {
    const paths = extractPaths(p.MyContainer);
    return paths.some(path => placePaths.includes(path));
  })
  .values;

// 4b) Direct People: whose MyContainer links **directly** to this Hub
const direct = dv.pages(`"2-World/People"`)
  .where(p => extractPaths(p.MyContainer).includes(hubPath))
  .values;

// 5) Merge & dedupe by file path
const allPeople = [...indirect, ...direct];
const unique = Array.from(
  new Map(allPeople.map(p => [p.file.path, p])).values()
);

// 6) Build rows (Name clickable, Race, Gender, Associated Group)
const rows = unique.map(p => {
  const linkEl = dv.el("a", p.file.name, {
    href: "#",
    cls: "dataview-link",
  });
  linkEl.addEventListener("click", e => {
    e.preventDefault();
    app.workspace.openLinkText(p.file.path, dv.current().file.path);
  });

  const race = p.char_race ?? "";
  const gender = p.char_gender ?? "";
  let groups = p.Connected_Groups ?? [];
  if (!Array.isArray(groups)) groups = [groups];
  const assoc = groups.join(", ");

  return [linkEl, race, gender, assoc];
});

// 7) Render the table
dv.table(
  ["Name", "Race", "Gender", "Associated Group"],
  rows
);
```

# GM Notes

Bryn Shander is the largest of ten settlements known collectively as Ten-Towns, located in the frigid heart of Icewind Dale. Here, caravans from the south converge with traders from across Icewind Dale to swap goods and rumors. Fishers, trappers, furriers, and sellswords rub elbows in the town’s taprooms, and gruff dwarves, wide-eyed travelers, and skulking ne’er-do-wells wander its streets. Merchants from the south trade dyes, hardwood, dried herbs and spices, textiles, fruits, wines, and other commodities for scrimshaw and other items made from the bones of the knucklehead trout that populate the region’s rivers and lakes.

The town is situated atop a hill south of the mountain known as Kelvin’s Cairn, a major landmark in Icewind Dale. From its windswept perch, Bryn Shander has a commanding view of the surrounding tundra, and an attacking force must climb the barren hillside under fire from archers before it can assault the outer wall. The circular wall that surrounds Bryn Shander stands 30 feet high and is made of tight-fitting stone blocks. Defenders stand atop a planked walkway that hugs interior of the wall. Spaced along the wall are stone watchtowers, wherein guards can take shelter during blizzards and warm their hands and feet by iron stoves.

The buildings of Bryn Shander are plain wooden structures with pitched rooftops to keep snow from settling on them. Clouds of white smoke issue forth day and night from stone chimneys and holes in rooftops.

# Travel

%% For every other hub/location that you would like to see travel time to, add a line in the table and replicate the format provided. Change the Town name and link it to that towns note and then change the 88 in the formula to match the distance in miles to that place. Use a Leaflet map to measure the distance. %%

`VIEW[{Travel Calculator#HoursPerDay}][math]` hrs per day
[[Travel Calculator]]  / [[Exhaustion]] Level: `VIEW[{Travel Calculator#ExhaustionLevel}][math]`

| Destination |  Travel Days  |
| ---|---|
| [[Next Town A]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
| [[Next Town B ]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`

# CAMPING 

C - Commerce (Economics and Entertainment) - Shops, Malls, Theatres, Markets, Carnivals, Electronics
A - Agriculture (Resource Production and Collection) - Farms, Mines, Fisheries, Lumber Yards, Oil Rigs, Power Plants
M - Military (Protection and Transportation) - Forts, Bases, Armories, Walls, Seaports, Airports, Spaceports
P - Philosophy (Religion and Education) - Houses of Worship, Schools, Universities, Laboratories, Arboretums
I - Industrial (Resource Utilization and Processing) - Factories, Metalworks, Bakeries, Artisans, Jewelers
N - Nesting (Housing and Civil Engineering) - Residential Areas, Inns/Hotels
G - Government (Legislation and Judicial) - Town Halls, Courthouses, Tourist Stops, Monuments/Landmarks

## Commerce

This is the content

`BUTTON[button_place]` `BUTTON[button_person]` **C - Commerce** (Economics and Entertainment) - Shops, Malls, Theatres, Markets, Carnivals, Electronics

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Commerce"
SORT file.name ASC
```

## Agriculture

`BUTTON[button_place]` `BUTTON[button_person]` **A - Agriculture** (Resource Production and Collection) - Farms, Mines, Fisheries, Lumber Yards, Oil Rigs, Power Plants

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Agriculture"
SORT file.name ASC
```

## Military

`BUTTON[button_place]` `BUTTON[button_person]` **M - Military** (Protection and Transportation) - Forts, Bases, Armories, Walls, Seaports, Airports, Spaceports

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Military"
SORT file.name ASC
```


## Philosophy

`BUTTON[button_place]` `BUTTON[button_person]` **P - Philosophy** (Religion and Education) - Houses of Worship, Schools, Universities, Laboratories, Arboretums

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Philosophy"
SORT file.name ASC
```

## Industrial

`BUTTON[button_place]` `BUTTON[button_person]` **I - Industrial** (Resource Utilization and Processing) - Factories, Metalworks, Bakeries, Artisans, Jewelers

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Industrial"
SORT file.name ASC
```

## Nesting

`BUTTON[button_place]` `BUTTON[button_person]` **N - Nesting** (Housing and Civil Engineering) - Residential Areas, Bridges, Parks, Inns/Hotels

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Nesting"
SORT file.name ASC
```

## Government

`BUTTON[button_place]` `BUTTON[button_person]` **G - Government** (Legislation and Judicial) - Town Halls, Courthouses, Tourist Stops, Monuments/Landmarks

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Government"
SORT file.name ASC
```



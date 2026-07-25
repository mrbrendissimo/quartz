---
tags:
  - Category/PointofInterest
MyContainer:
  - "[[Jungle of Screams|Jungle of Screams]]"
MyCategory: Encounter
obsidianUIMode: preview
mapCalc1: NaN
---

<%*
/* 1) Prompt for POI name */
const poiName = await tp.system.prompt("Enter Point of Interest Name", tp.file.title);
if (!poiName) return;                     // cancel if blank
await tp.file.rename(poiName);             // rename the file

/* 2) Gather and pick a container region */
const regionFiles = tp.app.vault.getMarkdownFiles()
  .filter(f => f.path.startsWith("2-World/Regions/"));
const regionChoices = regionFiles.map(f => f.basename);
const regionValues  = regionFiles.map(f => f.path);
const chosenPath    = await tp.system.suggester(regionChoices, regionValues, true);
if (!chosenPath) return;                   // cancel if none chosen

/* 3) Build full wiki-link for MyContainer */
const regionAlias = chosenPath.split("/").pop().replace(/\.md$/, "");
const regionLink  = `[[${chosenPath}|${regionAlias}]]`;

/* 4) Write MyContainer into front-matter */
setTimeout(() => {
  const file = tp.file.find_tfile(tp.file.path(true));
  if (!file) return;
  app.fileManager.processFrontMatter(file, fm => {
    fm["MyContainer"] = regionLink;
  });
}, 100);
%>


> [!NOTE] Parent Region: `INPUT[suggester(optionQuery(#Category/Region)):MyContainer]`


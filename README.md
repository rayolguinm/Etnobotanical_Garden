# GreenStore: Restoration and Adaptive Reuse, Interior and Landscape Design

**Author:** Raymundo "R@y" Olguin  
**Location:** Puebla  
**Revision:** R7 (2026-10-24)

Project page for my volunteer social service as Architectural Designer for the outreach store of the Francisco Peláez R. Ethnobotanical Garden, Puebla (Jan to Jul 2022). The store is not a new building: it is the existing single-storey brick room the garden already owned, restored and reused. Its walls, slab, window openings and original pair of entrance doors are kept and repaired; only reversible fit-out, lime and terracotta finishes, a green roof, a living wall and an ethnobotanical forecourt garden are added.

Live page: `https://rayolguinm.github.io/<repository-name>/`  
Drawing set: [https://rayolguinm.github.io/greenstore-drawing-set/](https://rayolguinm.github.io/greenstore-drawing-set/)

## Repository structure

```
<repository>/
├── images/      2022 renders (JPG), drawings and concept graphics (SVG) used by the page
├── README.md    this file
└── index.html   the whole page; styles are inside the file, fonts load from Google Fonts
```

Three items, nothing else to set up. `index.html` only uses files in `images/` plus two links out: Google Fonts and the drawing-set site.

## What the page contains

01 Context · 02 Design Concept · 03 Design Principles · 04 Before and After · 05 Interior Design · 06 Entrance · 07 Modular System · 08 Architectural Drawings · 09 Landscape Design · 10 Furniture Design · 11 Drawing Set · 12 My Role · Purpose

* **Design concept, restore instead of rebuild:** a four-step order for every decision: Keep (the shell), Repair (doors, windows, brick joints), Reuse (reclaimed pine, salvaged brick and rubble), Add lightly (green roof, living wall, garden, all reversible). Supported by an exploded "existing and added" diagram, a restoration schedule (element, action, design intent) and a passive-strategies section (cross ventilation, stack effect through the high window, brick thermal mass, green roof, daylight, rainwater). Backed by two peer-reviewed life-cycle studies (C1, C2).
* **Interior design graphics:** moodboard, colour palette with hex codes and a 60 / 30 / 10 proportion bar, and a nine-sample material board tagged existing, reused, local or living.
* **Entrance D01:** the existing pair of glazed timber doors in its original opening is kept and repaired in place (2.10 x 2.40 m as drawn, 94.5 cm clear per leaf). No wall is cut and no lintel replaced.
* **Modular system:** the 15 cm base module M is read from the existing shell (walls, piers, openings and room all fall on it); tile grid 30 cm (2M), fit-out grid 60 cm (4M: S-600 shelving, D-600 desk, I-600 island, LW-600 living-wall panels), landscape module 1.20 m (8M).
* **Drawings:** setting-out axes and three levels of dimensions (elements, axis to axis, overall) on every orthographic drawing. Retained elements are labelled "existing, retained".
* **Single storey:** the roof is an extensive green roof reached for maintenance only; there is no stair, roof deck or upper level.
* **Landscape:** a 12.00 x 15.75 m forecourt on the building's axes with a 1.80 m axis walk. Strategy: keep the existing soil, balance levels on site, reuse salvaged brick and rubble, lay basalt pavers on sand, keep all roof water on site (1,100 L cistern and rain garden), and plant useful native species propagated where possible from the garden's own collection. 23 species, backed by peer-reviewed papers only.

## Files in images/

| File | Shows |
|---|---|
| `hero.jpg`, `counter.jpg`, `aerial.jpg`, `sections.jpg`, `desk.jpg` | 2022 renders |
| `concept-layers.svg` | Exploded diagram: existing, repaired, added and living layers |
| `passive-section.svg` | Schematic section of passive strategies |
| `material-board.svg` | Nine-sample material board |
| `concept-layers-m.svg`, `passive-section-m.svg`, `material-board-m.svg` | Phone versions of the three graphics above, with labels stacked below the drawing; the page swaps them in automatically below 640 px |
| `plan-diagram.svg`, `module-plan.svg`, `zoning.svg` | A-101, A-102, A-103 plans |
| `elevation-south.svg`, `elevation-west.svg` | A-201 elevations |
| `section-diagram.svg`, `long-section.svg` | A-301 sections |
| `interior-north.svg`, `interior-west.svg` | A-401 interior elevations |
| `door-window-details.svg` | A-501 existing door and windows |
| `furniture-modules.svg` | A-601 fit-out modules |
| `axon.svg` | A-901 cutaway isometric |
| `electrical.svg`, `irrigation.svg` | E-101 and P-101 |
| `landscape-plan.svg`, `planting-plan.svg`, `landscape-section.svg`, `landscape-details.svg` | L-101, L-102, L-301, L-501 |
| `module-diagram.svg`, `functional.svg` | Module hierarchy and functional diagram |

## Phone and tablet layout

Tested in iPhone emulation at 320, 375 and 390 px wide, plus iPad mini and desktop, with an automatic check for horizontal overflow and overlapping text (none found). On phones: the section menu scrolls sideways in one line; data tables (restoration schedule, modules, plant schedule) turn into stacked cards; the drawing-set index becomes a row of sheet chips; the colour proportion bar stacks; and the three concept graphics switch to their tall phone versions. Tap any drawing to open it full size and pinch to zoom.

## Units

| Where | Unit | Example |
|---|---|---|
| Plans, sections, elevations (1:50, 1:100) and levels | m | 3.60, +3.00 |
| Details (1:20) and schedules | cm | 105, 94.5, 60 x 60 cm |
| Material thicknesses, glass, pipes, fixings | mm | 6 mm glass, Ø 100 mm pipe |
| Base module | M = 15 cm | 2M 30 cm, 4M 60 cm, 8M 1.20 m |

## Key dimensions

| Item | Value |
|---|---|
| Interior | 3.60 x 5.70 m = 20.52 m² |
| Axes | A to B 3.90 m; 1 to 2 2.10, 2 to 3 1.80, 3 to 4 2.10 m |
| Walls / piers (existing) | 0.30 m brick; piers 0.30 x 0.45 m, corners 0.45 m |
| Heights | ceiling +3.00, cove +2.70, pendant +2.40, slab top +3.15, parapet +3.60 |
| D01 (existing, retained) | 2.10 x 2.40 m, 2 leaves of 1.05 m |
| Windows (existing, retained) | W01 1.20 x 1.20 (x4), W02 0.90 x 1.20 (x2), sill +0.90; W03 1.80 x 0.45 high window at +2.40 |
| Fit-out (added, reversible) | 12 x S-600, 3 x D-600, 3 x I-600, 9 x LW-600, 4 x PL-450 |

## Upload to GitHub

1. On GitHub, open the repository (or create an empty **public** one with "Add a README" unticked).
2. Click **Add file > Upload files**.
3. Open this folder on your computer, select `images`, `README.md` and `index.html` together, and drag them onto the page. If the repository already has these files, the upload replaces them; the `images` folder merges, so delete any old image GitHub still lists that is not in this folder (in particular `door-comparison.svg`, which is no longer used).
4. Click **Commit changes**.
5. **Settings > Pages > Build and deployment > Source: Deploy from a branch**, branch `main`, folder `/ (root)`, **Save**. The page goes live at `https://rayolguinm.github.io/<repository-name>/` after a minute or two.

The links to the drawing set point to `https://rayolguinm.github.io/greenstore-drawing-set/`. If the drawing set lives in a repository with another name, search `index.html` for `greenstore-drawing-set` and replace it with that name. The separate drawing-set site may still carry the older entrance story; update it to match.

## Status and limits

* Dimensions are design dimensions set to the module; the room was never surveyed for this set. Verify on site.
* The 2022 renders carry the client's logo.
* Green-roof load on the existing slab must be confirmed by a licensed structural engineer; electrical and plumbing layouts are indicative.
* Plan north is assumed.
* The concept, passive and material graphics are diagrams, not to scale.
* Portfolio presentation, not issued for construction.

## Sources

Concept: two peer-reviewed life-cycle studies on refurbishment versus demolition (C1 Gaspar and Santos 2015, C2 Assefa and Ambler 2017), listed in the Design Concept section. Landscape: the full numbered list of 25 peer-reviewed papers is in the Landscape section of the page and on sheet L-301 of the drawing set. Paper titles stay in their original language, as citations require.

© Raymundo "R@y" Olguin. All rights reserved.

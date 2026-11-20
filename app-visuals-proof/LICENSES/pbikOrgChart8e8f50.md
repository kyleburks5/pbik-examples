# Org chart (1.0.0.0)

Org chart that morphs into clusters by team or location: expand and collapse, find a person, zoom, click to filter.

| | |
| --- | --- |
| Visual id (guid) | `pbikOrgChart8e8f50` |
| Package | `pbikOrgChart8e8f50.1.0.0.0.pbiviz` (138 KB) |
| Visuals API | 5.11.0 |
| Author / support | pbip-kit pbip-kit@example.invalid / https://example.invalid/pbip-kit/support (placeholders until the organisation sets its own) |
| Privileges asked | none (no web access, no local storage, no downloads) |
| Network calls | none: the pbiviz certification audit found no external requests |
| Lint (eslint-plugin-powerbi-visuals, recommended) | clean |
| Kit bundle checks (eval, new Function, fetch, XHR, WebSocket, dynamic import, external fonts) | none found |
| Web addresses named in the bundle (not fetched) | 0 |

## Data roles

- **Item (one card per person)** (Grouping)
- **Parent (their manager's Item)** (Grouping)
- **Label (name on the card)** (Grouping)
- **Group A (cluster view 1)** (Grouping)
- **Group B (cluster view 2)** (Grouping)
- **Size** (Measure)
- **Tooltips** (Measure)

## Formatting pane

- colors: accent, background, text, byGroup, dimOpacity
- fonts: family, size, headlineSize
- layout: padding, gap, radius, shadow, markSize
- motion: animate, speed, easing, stagger, reduceMotion
- interaction: tooltips, brush, zoom, clickMode, filterField
- tree: layout
- debug: meter, selfTest

Saved with the report and in bookmarks: the `state` object (view, drill, camera) and, in filter mode, the visual's filter.

## Third-party code bundled

| Package | Version | Licence |
| --- | --- | --- |
| d3-array | 3.2.5 | ISC |
| d3-brush | 3.0.1 | ISC |
| d3-ease | 3.0.2 | BSD-3-Clause |
| d3-flextree | 2.1.2 | WTFPL |
| d3-force | 3.0.1 | ISC |
| d3-hierarchy | 3.1.3 | ISC |
| d3-interpolate | 3.0.2 | ISC |
| d3-quadtree | 3.0.2 | ISC |
| d3-scale | 4.0.3 | ISC |
| d3-selection | 3.0.1 | ISC |
| d3-timer | 3.0.2 | ISC |
| d3-zoom | 3.0.1 | ISC |
| powerbi-models | 2.2.0 | MIT |
| powerbi-visuals-utils-formattingmodel | 6.2.2 | MIT |
| powerbi-visuals-utils-formattingutils | 6.1.2 | MIT |

d3-flextree is WTFPL (permissive, but some legal teams don't accept it). The visual also bundles d3-hierarchy's own tree layout (ISC): Format pane > Tree > Tree layout > Standard (d3.tree) uses only ISC code for the layout. If WTFPL isn't accepted, set Standard on every copy of the visual, or ask for a build without d3-flextree.

Template code: MIT, started from Microsoft's Dot Plot visual (NOTICE.md).

## Screenshots (the visual's golden harness screenshots)

![highcontrast-hc-clusters.png](screenshots/highcontrast-hc-clusters.png)
![highcontrast-hc-tree.png](screenshots/highcontrast-hc-tree.png)
![phone-phone-clusters.png](screenshots/phone-phone-clusters.png)
![phone-phone-tree.png](screenshots/phone-phone-tree.png)
![resize-after-resize.png](screenshots/resize-after-resize.png)
![scenario-01-tree.png](screenshots/scenario-01-tree.png)
![scenario-02-expanded.png](screenshots/scenario-02-expanded.png)
![scenario-03-by-team.png](screenshots/scenario-03-by-team.png)
![scenario-04-by-location.png](screenshots/scenario-04-by-location.png)
![scenario-05-found.png](screenshots/scenario-05-found.png)
![scenario-06-filtered.png](screenshots/scenario-06-filtered.png)
![scenario-07-d3tree.png](screenshots/scenario-07-d3tree.png)

## Version notes

## 1.0.0.0
- First version, made with pbip-kit's app-visual template.


# Deal dots (1.0.0.0)

Made with pbip-kit's app-visual template (docs/design/app-visuals.md).

| | |
| --- | --- |
| Visual id (guid) | `pbikP2V06DealDots8bc17b` |
| Package | `pbikP2V06DealDots8bc17b.1.0.0.0.pbiviz` (145 KB) |
| Visuals API | 5.11.0 |
| Author / support | pbip-kit pbip-kit@example.invalid / https://example.invalid/pbip-kit/support (placeholders until the organisation sets its own) |
| Privileges asked | none (no web access, no local storage, no downloads) |
| Network calls | none: the pbiviz certification audit found no external requests |
| Lint (eslint-plugin-powerbi-visuals, recommended) | clean |
| Kit bundle checks (eval, new Function, fetch, XHR, WebSocket, dynamic import, external fonts) | none found |
| Web addresses named in the bundle (not fetched) | 0 |

## Data roles

- **Item (one dot per row)** (Grouping)
- **Group** (Grouping)
- **Stage** (Grouping)
- **X** (Measure)
- **Y** (Measure)
- **Size** (Measure)
- **Tooltips** (Measure)

## Formatting pane

- colors: accent, background, text, byGroup, dimOpacity
- fonts: family, size, headlineSize
- layout: padding, gap, radius, shadow, markSize
- motion: animate, speed, easing, stagger, reduceMotion
- view: initial, pills, headline, labels, maxItems, order, customOrder
- interaction: tooltips, brush, zoom, clickMode, filterField
- debug: meter, selfTest

Saved with the report and in bookmarks: the `state` object (view, drill, camera) and, in filter mode, the visual's filter.

## Third-party code bundled

| Package | Version | Licence |
| --- | --- | --- |
| d3-array | 3.2.5 | ISC |
| d3-brush | 3.0.1 | ISC |
| d3-ease | 3.0.2 | BSD-3-Clause |
| d3-force | 3.0.1 | ISC |
| d3-interpolate | 3.0.2 | ISC |
| d3-quadtree | 3.0.2 | ISC |
| d3-scale | 4.0.3 | ISC |
| d3-selection | 3.0.1 | ISC |
| d3-timer | 3.0.2 | ISC |
| d3-zoom | 3.0.1 | ISC |
| powerbi-models | 2.2.0 | MIT |
| powerbi-visuals-utils-formattingmodel | 6.2.2 | MIT |
| powerbi-visuals-utils-formattingutils | 6.1.2 | MIT |

Template code: MIT, started from Microsoft's Dot Plot visual (NOTICE.md).

## Screenshots (the visual's golden harness screenshots)

![deals-01-grid.png](screenshots/deals-01-grid.png)
![deals-02-columns.png](screenshots/deals-02-columns.png)
![deals-03-scatter.png](screenshots/deals-03-scatter.png)
![deals-04-clusters.png](screenshots/deals-04-clusters.png)
![deals-05-selected.png](screenshots/deals-05-selected.png)
![deals-06-drill.png](screenshots/deals-06-drill.png)
![phone-phone-columns.png](screenshots/phone-phone-columns.png)
![phone-phone-grid.png](screenshots/phone-phone-grid.png)
![phone-phone-pinched.png](screenshots/phone-phone-pinched.png)
![resize-after-resize.png](screenshots/resize-after-resize.png)
![state-bookmark-restored.png](screenshots/state-bookmark-restored.png)
![state-filter-mode.png](screenshots/state-filter-mode.png)

## Version notes

## 1.0.0.0
- First version, made with pbip-kit's app-visual template.


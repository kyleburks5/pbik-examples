# Region panel (1.0.0.0)

Made with pbip-kit's app-visual template (docs/design/app-visuals.md).

| | |
| --- | --- |
| Visual id (guid) | `pbikP2V07AppPanel8c4170` |
| Package | `pbikP2V07AppPanel8c4170.1.0.0.0.pbiviz` (121 KB) |
| Visuals API | 5.11.0 |
| Author / support | pbip-kit pbip-kit@example.invalid / https://example.invalid/pbip-kit/support (placeholders until the organisation sets its own) |
| Privileges asked | none (no web access, no local storage, no downloads) |
| Network calls | none: the pbiviz certification audit found no external requests |
| Lint (eslint-plugin-powerbi-visuals, recommended) | clean |
| Kit bundle checks (eval, new Function, fetch, XHR, WebSocket, dynamic import, external fonts) | none found |
| Web addresses named in the bundle (not fetched) | 0 |

## Data roles

- **Group (one card each)** (Grouping)
- **Stage (the mini chart)** (Grouping)
- **Item (the detail list)** (Grouping)
- **Value** (Measure)
- **Tooltips** (Measure)

## Formatting pane

- colors: accent, background, text, byGroup, dimOpacity
- fonts: family, size, headlineSize
- layout: padding, gap, radius, shadow, markSize
- motion: animate, speed, easing, stagger, reduceMotion
- panel: columns, maxCards, miniChart, headline, what, listSize, tooltips, customOrder
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

![resize-after-resize.png](screenshots/resize-after-resize.png)

## Version notes

## 1.0.0.0
- First version, made with pbip-kit's app-visual template.


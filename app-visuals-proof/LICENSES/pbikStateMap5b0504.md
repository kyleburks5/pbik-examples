# Sites map (1.0.0.0)

US states map: shaded states, dots per site, and states that morph into sized bubbles; click to zoom and filter.

| | |
| --- | --- |
| Visual id (guid) | `pbikStateMap5b0504` |
| Package | `pbikStateMap5b0504.1.0.0.0.pbiviz` (183 KB) |
| Visuals API | 5.11.0 |
| Author / support | pbip-kit pbip-kit@example.invalid / https://example.invalid/pbip-kit/support (placeholders until the organisation sets its own) |
| Privileges asked | none (no web access, no local storage, no downloads) |
| Network calls | none: the pbiviz certification audit found no external requests |
| Lint (eslint-plugin-powerbi-visuals, recommended) | clean |
| Kit bundle checks (eval, new Function, fetch, XHR, WebSocket, dynamic import, external fonts) | none found |
| Web addresses named in the bundle (not fetched) | 1 |

## Data roles

- **Location (US state)** (Grouping)
- **Group (one dot each)** (Grouping)
- **Value (size)** (Measure)
- **Colour (shading)** (Measure)
- **Tooltips** (Measure)

## Formatting pane

- colors: accent, background, text, byGroup, dimOpacity
- fonts: family, size, headlineSize
- layout: padding, gap, radius, shadow, markSize
- motion: animate, speed, easing, stagger, reduceMotion
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
| d3-geo | 3.1.2 | ISC |
| d3-interpolate | 3.0.2 | ISC |
| d3-quadtree | 3.0.2 | ISC |
| d3-scale | 4.0.3 | ISC |
| d3-selection | 3.0.1 | ISC |
| d3-timer | 3.0.2 | ISC |
| d3-zoom | 3.0.1 | ISC |
| flubber | 0.4.2 | MIT |
| powerbi-models | 2.2.0 | MIT |
| powerbi-visuals-utils-formattingmodel | 6.2.2 | MIT |
| powerbi-visuals-utils-formattingutils | 6.1.2 | MIT |
| topojson-client | 3.1.0 | ISC |
| us-atlas | 3.0.1 | ISC |

flubber (MIT) has had no release since 2018; its dependencies are earcut (ISC), svgpath (MIT) and svg-path-properties (ISC).

Template code: MIT, started from Microsoft's Dot Plot visual (NOTICE.md).

## Screenshots (the visual's golden harness screenshots)

![highcontrast-hc-bubbles.png](screenshots/highcontrast-hc-bubbles.png)
![highcontrast-hc-map.png](screenshots/highcontrast-hc-map.png)
![resize-after-resize.png](screenshots/resize-after-resize.png)
![scenario-01-map.png](screenshots/scenario-01-map.png)
![scenario-02-bubbles.png](screenshots/scenario-02-bubbles.png)
![scenario-03-dots.png](screenshots/scenario-03-dots.png)
![scenario-04-zoom-texas.png](screenshots/scenario-04-zoom-texas.png)
![scenario-05-filtered-west.png](screenshots/scenario-05-filtered-west.png)

## Version notes

## 1.0.0.0
- First version, made with pbip-kit's app-visual template.


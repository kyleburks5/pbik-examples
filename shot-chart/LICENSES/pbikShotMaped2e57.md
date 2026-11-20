# Shot map (1.0.0.0)

Made with pbip-kit's app-visual template (docs/design/app-visuals.md).

| | |
| --- | --- |
| Visual id (guid) | `pbikShotMaped2e57` |
| Package | `pbikShotMaped2e57.1.0.0.0.pbiviz` (131 KB) |
| Visuals API | 5.11.0 |
| Author / support | pbip-kit pbip-kit@example.invalid / https://example.invalid/pbip-kit/support (placeholders until the organisation sets its own) |
| Privileges asked | none (no web access, no local storage, no downloads) |
| Network calls | none: the pbiviz certification audit found no external requests |
| Lint (eslint-plugin-powerbi-visuals, recommended) | clean |
| Kit bundle checks (eval, new Function, fetch, XHR, WebSocket, dynamic import, external fonts) | none found |
| Web addresses named in the bundle (not fetched) | 0 |

## Data roles

- **Item (one point per row)** (Grouping)
- **Zone (the model's zone or stage, for filtering)** (Grouping)
- **Group (judged against its own range)** (Grouping)
- **X** (Measure)
- **Y** (Measure)
- **Outcome (1 = success, 0 = not)** (Measure)
- **Benchmark rate (optional)** (Measure)
- **Order (tracks)** (Measure)
- **Tooltips** (Measure)

## Formatting pane

- colors: accent, background, text, dimOpacity, cold, hot
- fonts: family, size, headlineSize
- layout: padding, gap, radius, shadow, markSize
- motion: animate, speed, easing, stagger, reduceMotion
- interaction: tooltips, clickMode
- debug: meter, selfTest
- space: shape, scale, custom, start, pills, headline, readout, readoutWidth, labels, benchmarkSpan, standout
- honest: minSample, mode

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

![body-body-ranked.png](screenshots/body-body-ranked.png)
![body-body-zones.png](screenshots/body-body-zones.png)
![floor-floor-zones.png](screenshots/floor-floor-zones.png)
![highcontrast-high-contrast.png](screenshots/highcontrast-high-contrast.png)
![loading-loaded.png](screenshots/loading-loaded.png)
![loading-loading.png](screenshots/loading-loading.png)
![privacy-privacy.png](screenshots/privacy-privacy.png)
![scenario-01-zones.png](screenshots/scenario-01-zones.png)
![scenario-02-points.png](screenshots/scenario-02-points.png)
![scenario-03-ranked.png](screenshots/scenario-03-ranked.png)
![scenario-04-picked.png](screenshots/scenario-04-picked.png)
![scenario-05-gap.png](screenshots/scenario-05-gap.png)

## Version notes

## 1.0.0.0
- First version, made with pbip-kit's app-visual template.


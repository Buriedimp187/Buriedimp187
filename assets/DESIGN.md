# Design — "Buried"

Concept: a mark emerging from a horizon line; complexity stays below, the surface stays minimal. A short underscore under the line hints at a terminal prompt.

| Role | Hex |
| --- | --- |
| Background | `#0D1117` |
| Surface | `#161B22` |
| Border | `#30363D` |
| Text | `#E6EDF3` |
| Text secondary | `#8B949E` |
| Accent (ember) | `#FF5A36` |

Light variant (logo only): bg `#FFFFFF`, border `#D0D7DE`, text `#1F2328`, secondary `#656D76`, accent `#E8421C`.

Avatar: `logo-mark-1024.png` (transparent, exported from `logo-mark.svg` with headless Chromium; the SVG stays the editable source).

Rules: accent only on the mark; no effects; monospace system stack (`ui-monospace, Consolas, …`) because SVGs loaded via `<img>` cannot fetch web fonts.

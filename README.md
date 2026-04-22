# echo-media

Permanent public CDN for Echo's published / scheduled media assets.
Organized by `YYYY-MM-DD/{content-id}/` folders.

**Why this exists:** Metricool's media pipeline requires public URLs. This repo provides
stable, Ozni-owned raw URLs (via `raw.githubusercontent.com`) that Metricool can
fetch and cache on its own CDN (`static.metricool.com`).

**Contents are public by design.** Do not push anything sensitive.

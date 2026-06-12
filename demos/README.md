# Demos

**Updated Day 0:** demos ship inside the live site's repo (`wiresetweb/wireset-web`), served at wiresetweb.com. The four **website** demos (hvac, auto, restaurant, health) already exist there. **Tool** demos are new, live under `/demos/tools/`, and are staged in `wireset-web-changes/demos/tools/` in this repo until we have push access to wireset-web.

| Unit | What | Live path (once merged) | Status |
|------|------|------------------------|--------|
| QT-01 | Instant quote calculator (fictional "Hartline Electric") | `/demos/tools/quote-calculator/` | ✅ Built Day 0, staged |
| JB-02 | Job tracker | `/demos/tools/job-tracker/` | Planned Day 1 |
| BK-03 | Booking intake | `/demos/tools/booking-intake/` | Planned Day 1–2 |

Conventions for tool demos (matching the existing repo):
- Fictional business, clearly banner-labeled as a demo with sample data
- `<meta name="robots" content="noindex" />` (site-wide robots.txt allows crawlers specifically so per-page noindex works)
- Brand per the repo's `BRAND.md` — navy #0b1a2e, amber #f5a524, system fonts, pill buttons
- Footer links back to `/tools/`

# STATE

**Day:** 1 of 14 (started 2026-06-11)
**Phase:** 2 — Demand generation. Assets done; both demand engines built; ads blocked on the Meta account, outreach blocked only on Laz's send.
**Cash position:** $100.00 of $100.00 remaining (no spend yet). Revenue: $0.

## ⚠ Read this first
Wireset Web is an **existing live business** — wiresetweb.com sells websites to local service businesses (3 tiers, $499–$1,299 + monthly) plus **$350 / 48-hour custom internal tools**. Cloudflare Worker `wireset-web`, auto-deploys from `wiresetweb/wireset-web` main. Brand: that repo's `BRAND.md`. Story: DECISIONS.md #6–#11.

## ⚠ Positioning (changed Day 1 — DECISIONS #11)
**Never pitch customer-facing pricing.** The quote tool is the contractor's **private quote builder** (pricing stays private; they approve every quote). Two ad landing pages, both live: `/go/quote-tool/` (specific) and `/go/custom-tools/` (broad "automate your busywork"). All copy, creatives, and templates follow this.

## What's live on wiresetweb.com (PRs #5–#15, all merged)
- Full site: tools line, overhaul, interactive layer, 14-post blog, branded OG/schema/sitemap.
- **Two ad landing pages** with UTM lead tagging (`source` distinguishes them) — forms live-verified by Laz ✅.
- **Demo = private quote builder with a real cost engine** (global labor rate + materials markup; per-item hours, materials, feet-of-wire; live recompute): `/demos/tools/quote-calculator/`.
- **$175 deposit Stripe link live** on `/tools/` ✅.

## Demand engine status
| Channel | State | Blocking |
|---|---|---|
| **Paid ads** | Plan + 21 creatives v2 + placement copy + spend priority done (`strategy/ad-plan.md` §11–14) | Laz: Meta account (HUMAN_TASKS #3) |
| **Cold outreach** | **61 prospects** w/ observable pains (`strategy/prospects.md`), templates v2 (`outreach/templates/cold-first-touch.md`), **top-10 drafts ready** (`outreach/drafts/2026-06-12-first-batch.md`) | Laz: verify + send (HUMAN_TASKS #4, ~30 min) |

## Top 3 priorities (Day 2)
1. **Send the first 10 outreach emails** (Laz, HUMAN_TASKS #4) — free, ready now, ~30 min.
2. **Meta ad account → launch $35 Tranche A** (Laz, HUMAN_TASKS #3) — quote-builder ads, elec/plumb/carp → `/go/quote-tool/`.
3. **Next 10 outreach drafts** from the A-list (agent) + reply handling if any come in (speed-to-lead: `ad-lead-followup.md`).

## Blockers (all on Laz)
- Meta Business + ad account · First-10 sends · Final-50% Stripe link + portal URL

## Where things live
- Prospects: `strategy/prospects.md` (61 rows; **re-verify in a browser before any send** — sourced from search snippets) · Drafts: `outreach/drafts/` · Templates: `outreach/templates/cold-first-touch.md` (v2; old base template superseded)
- Ad plan: `strategy/ad-plan.md` · Creatives: `strategy/ads/` (broad_*, quote_*, parked book_*/order_*) · Ad-lead emails: `outreach/templates/ad-lead-followup.md`
- Tasks for Laz: `ops/HUMAN_TASKS.md` · Money: `ops/ledger.md` · Logs: `ops/daily/` · Decisions: `DECISIONS.md` (latest #11: repositioning)
- Container egress note: arbitrary web fetches are blocked (search snippets only); Canva/Web3Forms/image CDNs also blocked. Venture repo can't be pushed from the session — deliver via `git format-patch` → Laz applies with `git am`.

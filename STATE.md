# STATE

**Day:** 0 (started 2026-06-11)
**Phase:** 1 — Foundation (Days 0–2), but ~80% pre-met — see below
**Cash position:** $100.00 of $100.00 remaining (no spend; domain & infra already owned)

## ⚠ Read this first (major Day-0 correction)
Wireset Web is an **existing live business**, not a name we invented. wiresetweb.com sells websites to local service businesses (3 tiers, $499–$1,299 build + monthly), has 4 live industry demos, a working contact form, and a live hello@ email. It runs on Cloudflare Worker `wireset-web`, auto-deployed from the `wiresetweb/wireset-web` GitHub repo's `main` branch via Workers Builds. Brand rules live in that repo's `BRAND.md` (navy + amber, system fonts, pill buttons, plain-spoken voice) — **all customer-facing work must follow it**. Full story: DECISIONS.md #6–#9.

**The mission is now a hybrid:** add the $350-flat / 48-hour custom internal tool offer as a new service line on the existing site, and sell both (websites AND tools) in outreach.

## Assets in hand
- Live branded site + 4 website demos + working Web3Forms contact form ✅
- hello@wiresetweb.com live ✅
- **Staged & ready to ship** in `wireset-web-changes/` (drop-in files for the wireset-web repo): homepage with Tools section, `/tools/` page, on-brand quote-calculator demo, updated sitemap
- Local clone of the live site at /tmp/wireset-web (ephemeral — re-clone if container reset: `git clone https://github.com/wiresetweb/wireset-web`)

## Top 3 priorities
1. **Get `wiresetweb/wireset-web` added to this session** (HUMAN_TASKS #1, BLOCKING) → then I push the staged changes as a branch for Laz's review → merge = live
2. **Stripe**: $175 deposit/final payment links + fix the footer's placeholder billing-portal URL (HUMAN_TASKS #2, BLOCKING for taking money)
3. Build tool demos #2 (job tracker) and #3 (booking intake) under `/demos/tools/`

## Blockers
- wireset-web repo access (Laz — chose to grant it, not yet done)
- Stripe payment links (Laz)

## Phase gate status
Phase 1 → 2 gate: site live ✅ (already was) · tools offer visible on site ⏳ (staged, needs repo access + merge) · can accept payment ❌ (Stripe). Phase 2 prospect sourcing can start Day 1 in parallel.

## Where things live
- Offer: `strategy/offer.md` · Pricing: `strategy/pricing.md` (now includes website tiers)
- Staged site changes: `wireset-web-changes/` (mirrors wireset-web repo paths; see its README)
- Old dark concept: `archive/day0-dark-concept/` (superseded, kept for reference)
- Task queue for Laz: `ops/HUMAN_TASKS.md` · Money: `ops/ledger.md`
- Today's log: `ops/daily/day-00.md`

# DECISIONS (append-only)

## 1 — 2026-06-11 — Domain: use wiresetweb.com (already owned)
Laz already owns wiresetweb.com and the zone is on Cloudflare. Saves ~$12 and a day of waiting. Budget stays at a full $100.
**Rejected:** buying a new niche-specific domain — unnecessary spend and delay; the name works (see #2).

## 2 — 2026-06-11 — Brand: "Wireset Web"
Keep the domain name as the brand. "Wireset" reads naturally to the target niche (trades — wiring, electrical, setup) while "Web" says what we do. A coined compound name also looks like a real studio, not a side project. Laz approved using the name and gave latitude on the visual angle.
**Rejected:** inventing a second brand on a subdomain — splits credibility and wastes a real asset.

## 3 — 2026-06-11 — Visual direction: "schematic industrial"
Laz explicitly wants a site that makes people pause. Direction chosen: dark charcoal base, electric amber accent (hot wire / hi-vis safety palette), big condensed display type, monospace details, and an animated wire/circuit motif with a pulse of current. It speaks the customer's visual language (panel boards, schematics, jobsite) instead of generic SaaS pastels.
**Rejected:** standard light SaaS look (forgettable to this audience), and heavy WebGL effects (hurts load time on jobsite phones; the audience browses on mobile).

## 4 — 2026-06-11 — Offer: $350 / 48h with an explicit complexity valve
Default offer kept ($350 flat internal web tool, 48-hour delivery, one revision round) but with a hard caveat baked into the offer doc, site copy, and outreach templates: the $350/48h promise applies to a defined "standard scope" (single-purpose tool, one user role, no third-party integrations beyond email/CSV). Anything bigger gets an honest up-front custom quote and timeline before any money changes hands. Per Laz: never get trapped promising a complex build for $350 in 2 days.
**Rejected:** hourly pricing (kills the productized pitch) and raising the base price (unproven offer; prove demand first).

## 5 — 2026-06-11 — Demo #1: instant quote calculator for electrical contractors
Highest-leverage first demo: quoting is a universal, observable pain (phone-tag quotes, paper estimates), it demos well in 30 seconds, and it doubles as a sales artifact for the exact niche the brand name targets. Single static HTML file — runs free on Cloudflare Pages, works offline, nothing to break.
**Rejected:** starting with the job tracker (needs fake data to demo well) or booking intake (less differentiated; every booking SaaS does this).

## 6 — 2026-06-11 — CORRECTION: Wireset Web is an existing live business; decisions #1–#3 partially superseded
Discovered (Laz clarified, then verified by cloning `wiresetweb/wireset-web`): wiresetweb.com is a **live site selling websites to local service businesses** — 3 tiers ($499+$49/mo, $799+$79/mo, $1,299+$129/mo), 4 industry demos, working Web3Forms contact form, live hello@ email, served by Cloudflare Worker `wireset-web` that auto-deploys from that repo's `main` via Workers Builds. There is a documented brand (`BRAND.md` in that repo: navy #0b1a2e + amber #f5a524, system fonts, pill buttons, plain-spoken blue-collar voice).
**Consequences:** the mission becomes a *hybrid* — add the $350/48h custom-tool offer as a new service line to the existing business. Decision #3's "schematic industrial" visual direction is dead; all customer-facing work follows the existing BRAND.md. Phase 1's gates were mostly already met before we started (site live, email live); the real remaining gate is Stripe. The Day-0 HUMAN_TASKS for domain/Pages/email were obsolete and have been replaced.

## 7 — 2026-06-11 — Integration: new service line on the existing site
Tools become a section + pricing card on the wiresetweb.com homepage, a `/tools/` detail page, and demos under `/demos/tools/`. One brand, one funnel; websites and tools cross-sell each other. Changes staged in `wireset-web-changes/` (this repo) until the wireset-web repo is added to this session.
**Rejected:** separate subdomain (splits the funnel and the credibility), demos-only (buries the new revenue line).

## 8 — 2026-06-11 — Tool pricing stays $350 flat, no monthly
Laz chose one-time flat over the site's build+monthly shape. Fastest path to the 14-day $1,000 goal; a monthly fee on a $350 product adds billing friction for pennies. The /tools/ page cross-references the website tiers for bundling instead. (Confirms decision #4's price.)
**Rejected:** $299 + $19/mo (slower to goal), bundle-discount pricing (premature — no clients yet to bundle).

## 9 — 2026-06-11 — Day-0 dark concept archived, not deleted
The original "schematic industrial" landing page + demo moved to `archive/day0-dark-concept/`. The calculator's logic was ported into the new on-brand demo; the visual concept is kept in case a future client wants that aesthetic.

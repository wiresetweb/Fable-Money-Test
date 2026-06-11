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

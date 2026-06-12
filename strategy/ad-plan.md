# Paid Ad Plan — turning $100 into a pipeline

> Written Day 0 (2026-06-11). Companion files: `outreach/templates/ad-lead-followup.md`
> (the email sequence), `strategy/offer.md`, `strategy/pricing.md`. Every dollar logged in
> `ops/ledger.md` **before** it's spent. All copy follows the wireset-web `BRAND.md`
> (navy + amber, plain-spoken, no hype) and the `claude.md` ethics rules (truthful claims,
> real demo, working opt-out, no invented facts).

---

## 0. TL;DR (the whole plan in ten lines)

- **Who we target:** owner-operators of home-service trades — **HVAC, electrical, plumbing** — 1–10 trucks, in Laz's metro. Not their customers. *Them.*
- **The wedge offer:** lead with the **$350 / 48-hour custom quote tool**, not the website. It's an impulse price, it's unique (nobody else advertises it), and we have a live demo that sells itself in 30 seconds.
- **Channel:** **Meta (Facebook + Instagram)**, not Google Search. With $100, Meta buys ~100–250 clicks and precise small-business-owner targeting; Google Search would burn the budget in ~10 clicks against agencies.
- **Funnel:** ad → `/go/quote-tool/` landing page (live-demo preview + lead form, UTM-tagged) → Laz replies within **1 business hour** with a personalized mockup → Stripe deposit ($175) → 48-hour build → **upsell the website**.
- **Spend in two gated tranches:** **$35 test**, then **$65 scale** only if the test clears the gate. Never exceed $100 without a logged decision.
- **Break-even:** one $350 tool = 3.5× the entire ad budget. One $799 website = 8×. We need *one* sale for this to be a win.

---

## 1. The person we're talking to (picture them)

**"Mike Reyes," 43. Owns Reyes Comfort Heating & Air — 4 trucks, 6 guys, founded 2014.**

- He's the owner, dispatcher, top tech, and bookkeeper. He quotes jobs from his phone between service calls and answers "how much for a new unit?" texts at 9pm from his recliner.
- His web presence is a Facebook page with 230 followers and a website his wife's cousin built on Wix in 2019. It loads slow, the phone number is wrong, and he knows it. He's been "meaning to fix it" for two years.
- He's **booked solid June–August and dead in the shoulder seasons.** Marketing only crosses his mind when the phone goes quiet — which is exactly when money's tight, which is exactly when he distrusts anyone trying to sell him marketing.
- He has been **burned**: a "$299/month SEO" guy who showed him a report he didn't understand and produced nothing he could point to. A web "agency" that wanted $6,000 and six weeks. He now assumes anyone selling websites is either a kid with a template or a slick upseller.
- **He decides in three seconds and one thumb.** If an ad sounds like agency fluff ("elevate your digital presence"), he scrolls. If it sounds like a guy who actually gets the trade, names his exact pain in plain English, and shows him a *real working thing* he can poke at — he stops.
- What he actually wants: **fewer 9pm pricing texts, to look legit when a customer Googles him, and to not get ripped off.** He'll spend money fast on a tool that obviously pays for itself; he'll stall forever on a vague "website project."

**What this persona dictates about the ads:**
1. Lead with *his* pain in *his* words, not our features.
2. Show, don't tell — the demo link is the hero, not a brochure.
3. Plain, flat pricing on the face of the ad. Hiding the price reads as "expensive."
4. Kill the agency smell. Talk like a tradesperson. One honest human, not a "team."
5. Make the first step tiny (try a demo), not scary (book a consultation).

---

## 2. Strategic choices (and why)

### 2a. Why the $350 tool is the wedge, not the website
The website is the bigger sale ($499–$1,299 + monthly) but it's a *considered* purchase — Mike stalls on it. The $350 tool is a **tripwire**: small, concrete, novel, and impulse-priced. It gets him to say yes once, experience that we actually deliver in 48 hours, and *then* we're the obvious people to rebuild his site. The funnel sells the tool and **upsells the website** in follow-up (and on the `/tools/` page itself, which already cross-links the website tiers). This also matches our strongest, most tangible demo (the quote calculator).

### 2b. Why Meta, not Google Search (for a $100 budget)
- **Google Search** for "[trade] website" is owned by agencies bidding $6–15/click. $100 ≈ 8–15 clicks. Too thin to learn anything, and the intent is "I'm already shopping for a site" (rare for Mike, who isn't actively searching).
- **Meta** lets us *interrupt* Mike where he already is (Facebook is the trades' social network), target by business-owner signals + trade interests, show a visual demo, and pay **$0.40–$1.50/click**. $100 ≈ 100–250 clicks = enough to actually learn and convert. Demand-generation beats demand-capture when the buyer isn't searching yet.
- **Google is the *next* budget**, funded by revenue, once we know the message converts. Noted, not now.

### 2c. Why home-service trades (HVAC / electrical / plumbing) first
- High job values → $350 is trivial and $799 is easy to justify ("one service call covers it").
- The "call for pricing / 9pm quote text" pain is real, universal, and *visible* in their current web presence (easy to reference truthfully).
- We have matching demos: the quote-calculator (electrical "Hartline Electric") and the HVAC website demo.
- Cleanly targetable on Meta. If HVAC underperforms, electrical and plumbing are drop-in swaps for the same creative.

---

## 3. Budget: two gated tranches (max $100)

| Tranche | Spend | Duration | Purpose | Gate to proceed |
|--------|-------|----------|---------|-----------------|
| **A — Test** | **$35** | 5–7 days @ $5–7/day | Validate ad → click → demo/lead. Learn which creative + audience works. | Proceed to B only if: **CTR ≥ 1%**, **cost-per-landing-click ≤ ~$1.25**, and **≥ 1 real lead** (form fill or a demo-viewer who replied). |
| **B — Scale** | **$65** | 7–10 days @ ~$7–9/day | Pour budget into the winning creative/audience; add a **retargeting** ad to demo-viewers/site-visitors. | Ongoing: keep if **cost-per-lead ≤ $25** and pipeline is forming. |

**Hard rules**
- Total paid media **≤ $100**, ever, this venture. Log each top-up in `ops/ledger.md` before Laz adds it.
- **Gate discipline (mirrors `claude.md`'s Day-5 rule):** if Tranche A misses the gate, **do not spend harder** — rewrite the creative, swap the audience/trade, or fix the landing step first. Diagnose, then re-launch.
- If **$100 is spent with zero leads**, that's a pivot trigger → write a memo in `DECISIONS.md` (better niche, better hook, or back to pure cold-email outreach which costs $0).

**The math that makes this low-risk:** average cost-per-lead target ≈ $15–25. Even a **1-in-10** lead→sale rate at $25/lead = **$250 to land a $350 tool** (or an $799 site). One sale returns 3.5–8× the entire budget. We are not gambling; we're buying cheap shots at a high-margin target.

---

## 4. Campaign structure (exact Meta setup)

**Objective:** Traffic (link clicks) for Tranche A — cheapest way to buy real visits and learn. Switch to **Leads** or **Sales (conversions)** in Tranche B once the Meta pixel has data. (Leads objective optimizes toward form-fills but needs the pixel warmed first; Traffic gets us moving on day one.)

```
Campaign: WW — Tools Wedge — HVAC (Traffic)
└─ Ad set A1: "Owners — Interests"
│    Geo: Laz's metro + 25 mi radius
│    Age 30–60, all genders
│    Detailed targeting: (Small business owners) AND
│      (HVAC OR Air conditioning OR Heating, ventilating, and air conditioning
│       OR Plumbing OR Electrician OR Home improvement OR Contractor)
│    Placements: Advantage+ (let Meta optimize) — FB feed, IG feed, Stories, Reels
│    Budget: $5/day
└─ Ad set A2: "Advantage+ broad" (Meta's audience-finding)
     Geo: same. Minimal targeting, let the algo find owners off the creative.
     Budget: $2/day (small, as a control)
   3 ad creatives per ad set (see §5), let Meta rotate and find the winner.
```

**Tranche B additions**
```
└─ Ad set B-RT: "Retargeting"
     Audience: visited wiresetweb.com/tools/ OR /demos/tools/* OR engaged with our
     FB/IG in last 30 days, who did NOT submit the form.
     Creative: the "you tried the calculator…" follow-up ad (§5, creative 4).
     Budget: ~$3/day. (Retargeting is the cheapest, highest-converting money here.)
```

**Tracking:** every ad URL carries UTMs so we can read results in the form notifications and (later) analytics:
`https://wiresetweb.com/tools/?utm_source=meta&utm_medium=cpc&utm_campaign=tools_wedge_hvac&utm_content=<creative_id>`
The `/tools/` contact form already posts source="Tools page"; add the campaign via a hidden UTM field (small build — see §9 "to build").

---

## 5. The creative (ready-to-run copy)

Brand voice: short, declarative, plain. Amber accent, navy base. The demo link is the hero.
Starter images generated in `strategy/ads/` (square 1080×1080 + the OG cards). Iterate from there.

### Creative 1 — "The 9pm text" (primary)
**Primary text:**
> Still typing out prices from your recliner at 9pm?
>
> We'll build your shop a quote calculator your customers use themselves — they pick the job, see your price, and send it to you as a real request. Built around *your* services and *your* prices.
>
> $350 flat. Live in 48 hours. No monthly fee.
> Try a real one (30 seconds, works on your phone) 👇
**Headline:** Your prices, on autopilot
**Description:** Wireset Web — built for the trades
**CTA button:** Learn More → `/tools/?utm…`

### Creative 2 — "Call for pricing" (pain/credibility)
**Primary text:**
> "Call for pricing" is costing you the after-hours customer who wasn't going to call.
>
> Give them an instant quote on your site instead — and look like the most buttoned-up shop in town while you're at it. Custom-built around your services, $350 flat, delivered in 48 hours.
>
> See a live demo for a sample electrical contractor 👇
**Headline:** Quote jobs while you sleep
**CTA button:** Learn More

### Creative 3 — "Looks legit" (the website cross-sell hook)
**Primary text:**
> When a customer Googles you, what do they find — a slow page your cousin made in 2019, or a site that makes you look like the pro you are?
>
> We build fast, mobile-ready sites (and custom tools) for local trades. You own it outright. No contracts, no rental traps.
>
> See our work — loads in about a second on your phone 👇
**Headline:** Look as good as your work
**CTA button:** Learn More → homepage (`/?utm…`)

### Creative 4 — Retargeting only ("you tried it")
**Primary text:**
> Saw you checked out the quote calculator 👀
>
> Yours would have your services and your prices — and it'd be live in 48 hours for $350 flat. Want to see a mockup with your actual jobs in it? No cost to look.
**Headline:** Let's build yours
**CTA button:** Get a free mockup → `/tools/#contact`

**Format notes:** single image or a 10–15s screen-recording of the calculator being used (video usually beats static on Meta — a quick phone capture of the live demo is ideal and free to make). Always label honestly: the demo is a *sample* business.

---

## 6. The customer flow, start to finish

```
[1] Meta ad (Mike scrolling at 8pm)
        │  pain in his words + $350/48h + "try a real one"
        ▼
[2] Tap → /tools/?utm  (the live Tools page)
        │  Two things he can do, both low-friction:
        ├─(a) Tap "Try a live tool demo" → /demos/tools/quote-calculator/
        │        plays with it 30s → impressed → scrolls back → form
        └─(b) Scrolls to the form: "What's your paper form?"
        ▼
[3] Submits form (name, business, email, phone, the pain)
        │  Web3Forms → hello@wiresetweb.com + (to add) instant owner notification
        ▼
[4] AUTO-REPLY fires instantly: "Got it — a real person (not a bot) will reply
        within one business hour with an idea for [business]." (sets expectation,
        buys time, signals legit)
        ▼
[5] LAZ replies within 1 business hour  ← speed-to-lead is the whole game
        │  personalized: names their trade, proposes the exact tool, re-links demo,
        │  states $350/48h + the complexity-valve honesty line (offer.md)
        ▼
[6] Reply / quick call → scope against the 5 boundaries (offer.md)
        ▼
[7] Stripe deposit link ($175) → 48-hour build clock starts
        ▼
[8] Deliver tool ≤48h → final $175 → handoff doc
        ▼
[9] UPSELL + REFERRAL: "Want the website to match?" + "Know one other shop owner
        who'd use this?"  → feeds website pipeline + next leads
```

**Non-converters are not wasted:**
- Tried the demo but didn't submit → **retargeting ad (Creative 4)** + (if we captured email anywhere) the nurture sequence.
- Submitted but went quiet → **email follow-up sequence** (§7).
- Not ready at all → they've seen the brand; cheap future re-touch.

---

## 7. Follow-up email sequence

Full copy lives in **`outreach/templates/ad-lead-followup.md`**. Summary of the cadence (all sent from Laz's real identity, all personalized, all with a one-line opt-out):

| When | Email | Job |
|------|-------|-----|
| Instant (auto) | **Auto-acknowledge** | "We got it, a human replies within the hour." Sets the speed expectation. |
| Within 1 business hr | **#1 — The personal reply** | Names their trade + the exact tool, re-links the demo, price + 48h + honesty line. *This is the one that closes.* |
| +2 days (no reply) | **#2 — The concrete nudge** | "Here's roughly what yours would look like" — one specific example with their services. |
| +4 days | **#3 — Handle the objection** | Pre-empts "too good to be true / too busy": the complexity valve, the 48h promise, you own it. |
| +7 days | **#4 — The break-up** | "Should I close your file?" — the highest-reply email in the whole sequence. |
| Post-sale | **#5 — Delivery + upsell + referral** | Hand off, ask for the website, ask for one referral. |

---

## 8. Measurement — the one dashboard to watch

Track these in `ops/daily/` during the campaign. Targets are starting hypotheses, refined with real data.

| Metric | What it tells us | Starting target |
|--------|------------------|-----------------|
| CTR (link) | Is the creative stopping the scroll? | ≥ 1% (≥1.5% is good on Meta) |
| Cost per link click | Are we buying cheap visits? | ≤ $1.25 |
| Landing → demo-try rate | Is the page selling the demo? | ≥ 25% |
| Landing → lead (form) rate | Is the page converting? | ≥ 5% |
| **Cost per lead (CPL)** | **The number that matters most** | **≤ $25** |
| Lead → reply/call rate | Is follow-up working? | ≥ 50% |
| Cost per sale (CAC) | The bottom line | ≤ $175 (= half a tool) is excellent |

**Decision gates**
- **After $35:** hit the §3 gate → scale. Miss it → diagnose & fix one variable (creative / audience / trade / landing), relaunch the test. Don't just add money.
- **After $100:** ≥1 sale or a real pipeline → keep going on **revenue**, and open a Google Search test. Zero leads → pivot memo in `DECISIONS.md`.

---

## 9. What Laz must do vs. what's already done / I'll do

**Already built (the funnel exists today):** live `/tools/` page with the working demo + form, the quote-calculator demo, fast on-brand site, the $175 Stripe deposit link is live in the build step. We can point ads at `/tools/` **right now**.

**I (Claude) will produce / have produced — $0, no human needed:**
- This plan, the targeting spec, all ad copy (§5), the email sequence (`ad-lead-followup.md`), starter creative images (`strategy/ads/`).
- **To build next (in the wireset-web repo — I can push there):**
  - A hidden UTM field on the `/tools/` form so the campaign shows up in lead notifications.
  - ✅ **Built:** the dedicated landing page `/go/quote-tool/` (single offer, live-demo preview, one form with UTM capture, no nav, noindex). Live on wiresetweb.com. See §14 for the full landing-page plan.

**Laz must do (account / money / identity — per `claude.md` division of labor) — see `HUMAN_TASKS.md` #3:**
1. Create/confirm a **Meta Business Suite** account + Facebook Page for Wireset Web + an **ad account** with a payment method.
2. *(Recommended)* install the **Meta pixel** on the site (I'll provide the snippet + add it via the repo) so Tranche B can optimize for leads/sales.
3. Fund and **launch Tranche A ($35)** using the exact setup in §4 and creative in §5 (I'll hand it over copy-paste-ready).
4. Provide the **final-payment Stripe link** + the **billing-portal URL** (still open from Task #2) so the post-sale step is complete.
5. Paste daily numbers (spend, clicks, CTR, leads) back into the repo so I can read the gates and iterate the creative.

**Honesty / compliance guardrails (non-negotiable):**
- Every claim true: the demo is a *sample* business (labeled), "$350/48h" only attached to standard-scope tools, "you own it" is real.
- No fake urgency, no invented testimonials, no "trusted by 100s of shops."
- Meta: standard category (not Special Ad Category — we're not housing/employment/credit, so full targeting is allowed).
- The "AI does the grunt work, one human does the judgment" framing is already public on the site — keep it; it's *why* we can do $350/48h. It's a feature, not a secret.

---

## 10. Launch checklist (the first 60 minutes once the account exists)

- [ ] Page + ad account live, payment method added, spend cap set to **$100**.
- [ ] Pixel installed & firing (I add the snippet to the repo; Laz pastes the ID).
- [ ] UTM field added to the `/tools/` form (my build).
- [ ] Creatives 1–3 uploaded, each with its UTM link.
- [ ] Ad sets A1 ($5/day) + A2 ($2/day) built per §4.
- [ ] Auto-acknowledge reply configured (Web3Forms autoresponse or a saved Laz template).
- [ ] Laz's email-reply templates (`ad-lead-followup.md`) saved as drafts, ready to personalize.
- [ ] Daily-numbers note started in `ops/daily/`.
- [ ] **Go.** Read the gate at $35.

---

# 11. Creative kit — FINALS v2 (two angles; supersedes v1)

> **Why this changed.** v1 sold a *customer-facing* quote tool ("customers price their own work," "your website hands out prices"). That exposes a contractor's pricing publicly and locks them into a number before they've seen the job — the exact thing our buyer fears. Reframed into two honest angles, each with its own landing page.

Hand-composited from licensed photos + the real logo. Files in `strategy/ads/`, every concept in all three ratios. **Naming encodes the destination:** `broad_*` → `/go/custom-tools/`, `quote_*` → `/go/quote-tool/`, `book_*`/`order_*` → parked (see §14).

### Angle A — BROAD: "automate your busywork"  → `/go/custom-tools/`
Consultative. For mixed-trade audiences and interest targeting where a single specific tool wouldn't fit, and for retargeting.

| Concept | Image | Headline | Files (4:5 / 1:1 / 9:16) |
|---------|-------|----------|--------------------------|
| **Trades, general** | tool bag | "There's one job eating your week." | `broad_trades_4x5` · `broad_trades_1x1` · `broad_trades_9x16` |

### Angle B — INTERNAL QUOTE BUILDER: private, be-first, you stay in control  → `/go/quote-tool/`
Specific + safe. The tool is *yours*: price a job in two minutes on your phone, pricing stays private, you approve every number. **This is the higher-converting angle on cold traffic** (specificity sells) and carries no pricing-exposure baggage.

| Niche | Lever | Headline | Files (4:5 / 1:1 / 9:16) |
|-------|-------|----------|--------------------------|
| **Electrician** | Be first to the number | "Beat the other guy to the quote." | `quote_elec_4x5` · `quote_elec_1x1` · `quote_elec_9x16` |
| **Plumber / home-service** | Speed + privacy | "Price any job in two minutes." | `quote_plumb_4x5` · `quote_plumb_1x1` · `quote_plumb_9x16` |
| **Carpenter / remodeler** | Stop after-hours quoting | "Stop quoting from the couch." | `quote_carp_4x5` · `quote_carp_1x1` · `quote_carp_9x16` |
| **Product / screenshot** | Show the actual tool | "Price any job in two minutes." | `quote_demo_4x5` · `quote_demo_1x1` · `quote_demo_9x16` |

### Parked — booking & order (no pricing-exposure issue, but no LP/demo yet)
| Niche | Tool | Headline | Files | Status |
|-------|------|----------|-------|--------|
| **Wellness** | Booking | "Stay present. Let your site book the next client." | `book_spa_*` | hold → needs `/go/booking-tool/` + a booking demo |
| **Food truck** | Order-ahead | "That line is costing you sales." | `order_food_*` | hold → needs `/go/order-tool/` + an order demo |

**Which ratio goes where:** 4:5 → FB/IG **feed** (primary); 1:1 → feed fallback / Marketplace / Explore; 9:16 → **Stories & Reels** (image stands alone, built in safe zone).

**Screenshot ad (`quote_demo_*`):** shows the real internal builder — "Working quote · Private to you," line items, a job adjustment, the total, "this is your starting number." Headline, screenshot, and landing page now tell one story. (Earlier v1 used the customer-facing calculator and was pulled; the demo has since been rebuilt as the private builder — see §14.) Screenshot ads typically out-CTR photo ads because they show the actual product, so test `quote_demo_4x5` alongside the trade photos.

Design system (unchanged): photo fades to a solid navy band for guaranteed legibility; focal-point-aware crop keeps the subject above the band; amber accent on the payoff word; auto-fit offer pill; real logo top-left.

---

# 12. Placement copy — what goes where

Feed ads have three text fields plus the image; Stories/Reels show essentially just the creative. Hook ≤125 chars so it doesn't truncate.

### Angle B — quote builder → `/go/quote-tool/`

**Electrician**
- **Primary text:** "Most jobs go to whoever quotes first. Punch the job into your own quote builder and hand over a clean price in two minutes — right from the truck. Your pricing stays private; you send only the number you choose. $350 flat, live in 48 hours. 👇"
- **Headline:** Beat the other guy to the quote
- **Description:** Your private quote builder · $350
- **CTA:** Learn More
- **Link:** `https://wiresetweb.com/go/quote-tool/?utm_source=meta&utm_medium=cpc&utm_campaign=quote_builder&utm_content=elec`

**Plumber**
- **Primary text:** "Still writing quotes from the couch at 9pm? Build a clean, consistent price on your phone and send a professional quote before you've left the driveway. Your prices stay private — you stay in control. $350, live in 48 hours, you own it. 👇"
- **Headline:** Price any job in two minutes
- **Description:** Private to you · you own it
- **CTA:** Learn More
- **Link:** `…utm_campaign=quote_builder&utm_content=plumber`

**Carpenter / remodeler**
- **Primary text:** "Stop quoting from the couch. Build a clean, consistent quote in two minutes on your phone, then send it before the other guy has even called back. Your pricing stays private; you stay in control. $350 flat, 48 hours. 👇"
- **Headline:** Quote it before they call back
- **Description:** Your private quote builder · $350
- **CTA:** Learn More
- **Link:** `…utm_campaign=quote_builder&utm_content=carpenter`

### Angle A — broad → `/go/custom-tools/`

**Trades, general**
- **Primary text:** "There's one job eating your week — quoting, scheduling, booking, chasing parts. Tell us yours and we build a custom tool that handles it, around how you already work. Live in 48 hours, $350 flat, no monthly. 👇"
- **Headline:** We build the tool. You get your week back.
- **Description:** Custom tools for trades · $350
- **CTA:** Learn More
- **Link:** `https://wiresetweb.com/go/custom-tools/?utm_source=meta&utm_medium=cpc&utm_campaign=broad_busywork&utm_content=trades`

### Parked — wellness / food (use only after their LP is built)
- **Wellness → `/go/booking-tool/`:** "Your hands are full — let your website book the next client. Clients book the openings you choose; no phone tag, no DMs between sessions, you stay in control of your calendar. $350, 48 hours. 👇" · Headline: *Fill your calendar, not your voicemail*
- **Food truck → `/go/order-tool/`:** "Some customers won't wait in line — that's money walking off during your rush. Let them order from your menu online and skip the wait. You set the menu and the hours. $350, 48 hours. 👇" · Headline: *Don't let the line cost you sales*

---

# 13. Spend priority — how to allocate the $100

A $35 test can't read many signals at once. Concentrate, then widen.

1. **Tranche A ($35) — quote builder, trades only.** Run **Electrician + Plumber + Carpenter**, 4:5 and 9:16 each, all → `/go/quote-tool/`. This is the bet: specific message, highest-value buyers, one page, one offer. Specificity out-converts the broad pitch on cold traffic, so the specific angle leads.
2. **Read the gate (§3).** Winner = best cost-per-lead. Kill losers.
3. **Tranche B ($65) — scale the winner + add the broad set.** Pour budget into the winning trade. Add the **broad** creative (`broad_trades_*` → `/go/custom-tools/`) as (a) a **retargeting** ad to everyone who hit a quote-builder page and didn't convert, and (b) a small parallel test against *mixed-trade / interest* audiences where a single trade headline doesn't fit.
4. **Keep wellness/food off this budget.** Different buyer, different tool, different LP — they muddy the read and their landing pages aren't built. Deliberate later experiment.

**Priority if forced to pick:** Electrician ≥ Carpenter ≥ Plumber  →  then Broad (retarget/scale)  ≫  Wellness ≈ Food truck (later).

---

# 14. Landing pages — plan

**Principle:** every ad lands on a page that matches its promise. Message-match is the conversion.

**Built and live now:**
- **`/go/quote-tool/`** — reframed as the **internal quote builder** (private pricing, be-first, you approve every quote). For the elec / plumb / carp ads. UTM capture, `noindex`, `source = "Landing — Quote Builder"`.
- **`/go/custom-tools/`** — the **broad** "automate your busywork" page (example tools, "not sure what to automate?" path). For the broad ad + retargeting. UTM capture, `noindex`, `source = "Landing — Custom Tools"`.

**To build before funding those niches (same template, ~30 min each):**
- **`/go/booking-tool/`** — wellness. Needs a booking demo first.
- **`/go/order-tool/`** — food truck. Needs an order demo first.

**Ad → landing page map:**

| Ad | Landing page | Status |
|----|--------------|--------|
| `quote_elec_*`, `quote_plumb_*`, `quote_carp_*`, `quote_demo_*` | `/go/quote-tool/` | ✅ live (reframed internal) |
| `broad_trades_*` | `/go/custom-tools/` | ✅ live (new) |
| `book_spa_*` | `/go/booking-tool/` | ⏳ build + booking demo first |
| `order_food_*` | `/go/order-tool/` | ⏳ build + order demo first |

**✅ Resolved — quote demo rebuilt.** `/demos/tools/quote-calculator/` is now the contractor's **private quote builder** ("Working quote · Private to you" → tap the price book → job adjustment → professional quote you Copy/Text/Email). The demo, the `/go/quote-tool/` landing page, and the `quote_demo_*` screenshot ad now tell one consistent story. *Remaining demo builds:* a booking demo (for wellness) and an order demo (for food truck), each a prerequisite to running those niches.

**Measurement:** each ad's UTM flows into the lead's hidden `campaign` field and `source` names the page, so every inquiry is traceable to exact ad + niche + angle with no analytics setup.

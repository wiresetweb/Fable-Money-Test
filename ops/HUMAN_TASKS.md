# HUMAN TASKS — queue for Laz (newest at top)

Format per task: what, why, exact steps, what to paste back. Credentials go in `.env` (gitignored), never committed.

---

## 4. Verify + send the first 10 outreach emails — HIGH (free demand channel)
**Why:** 61 prospects with observable web pains are in `strategy/prospects.md`; the top 10 are fully drafted in `outreach/drafts/2026-06-12-first-batch.md`. Sourced from search snippets, so each needs a 60-second human check before sending.
**Steps (per email, ~3 min each):**
1. Open the prospect's page (URL in the draft) — confirm the claim is still true (e.g., still on the free subdomain / still Facebook-only).
2. Find the owner's first name if you can (reviews, about page) and fill the [brackets].
3. Run the honesty checklist at the bottom of `outreach/templates/cold-first-touch.md`.
4. Send from hello@wiresetweb.com (or their site form / FB message where noted — channel notes at the bottom of the drafts file).
5. Log it in `outreach/sent/` (date · business · variant · channel).
**Paste back:** which ones went out + any replies (forward replies to me for drafting responses).

## 3. Create the Meta ad account + launch the $35 test — BLOCKING (for paid ads)
**Why:** The full paid-ad plan is ready (`strategy/ad-plan.md`): targeting, budget gates, ad copy, creatives, the lead funnel, and the follow-up email sequence. I can't create accounts or spend money — that's yours. Once the account exists I hand you a copy-paste-ready campaign.
**Steps:**
1. Set up / confirm a **Facebook Page** for Wireset Web (if not already) and a **Meta Business Suite** account.
2. Create an **ad account**, add a payment method, and set the account **spend cap to $100** (hard ceiling for the whole venture).
3. *(Recommended)* Tell me to generate the **Meta pixel** snippet — I'll add it to the site via the repo; you paste the pixel ID back. This lets the scale phase optimize for leads.
4. Tell me "ad account ready" and I'll hand over the exact campaign setup (audiences, budgets) + the 3 creatives in `strategy/ads/` + UTM links, ready to upload.
5. Fund and **launch Tranche A ($35)**. Then paste daily numbers (spend, clicks, CTR, leads) into `ops/daily/` so I can read the gate and iterate.
**Paste back:** "ad account ready" + pixel ID (if doing step 3). Daily metrics during the run.

## 2. Stripe: finish the payment loop — BLOCKING (for final payment + footer billing)
**Why:** The **$175 deposit link is already live** on `/tools/` ✅ (you provided it). Two pieces remain.
**Steps:**
1. **Final-50% payment link:** Stripe → Products → "Wireset Web — Custom Tool (final 50%)" at **$175 one-time** → create a Payment Link.
2. **Customer portal URL:** Settings → Billing → Customer portal → activate → copy the portal login URL (looks like `https://billing.stripe.com/p/login/...`). The footer "Client billing" link is currently commented out, waiting on this.
**Paste back:** The final-payment link + the portal URL here (public URLs, safe to commit). I'll wire the portal URL into the live footer.

---

## Completed
- ✅ **#1 — Add the `wiresetweb/wireset-web` repo to the session.** Done — all staged work merged & auto-deployed (PRs #5–#9): Tools line, site overhaul, interactive layer, 14-post blog.
- ✅ **Stripe deposit link ($175).** Done — live on the `/tools/` page.
- ~~Buy domain~~ — already owned (pre-existing business)
- ~~Cloudflare Pages setup~~ — site already live via Worker `wireset-web` + Workers Builds
- ~~Email routing for hello@wiresetweb.com~~ — already live

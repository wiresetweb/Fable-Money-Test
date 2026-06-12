# HUMAN TASKS — queue for Laz (newest at top)

Format per task: what, why, exact steps, what to paste back. Credentials go in `.env` (gitignored), never committed.

> **2026-06-11 correction:** the original three Day-0 tasks (Cloudflare Pages setup, email routing, and parts of the Stripe task) were written before we knew wiresetweb.com was already live with working email. They're replaced by the two below.

---

## 2. Stripe: payment links + fix the broken footer billing link — BLOCKING (for taking money)
**Why:** We collect 50% of $350 ($175) before building any client tool. Also, the live site's footer "Client billing" link is a literal placeholder (`https://billing.stripe.com/p/login/REPLACE_WITH_STRIPE_PORTAL_URL`) — it 404s for anyone who clicks it today.
**Steps:**
1. Create/log into Stripe (sole proprietor is fine).
2. Products → add "Wireset Web — Custom Tool (50% deposit)" at **$175 one-time** → create a **Payment Link**. Repeat for "(final 50%)" at $175.
3. Customer portal: Settings → Billing → Customer portal → activate, and copy the portal login URL.
**Paste back:** The two payment-link URLs and the portal URL here (public URLs, safe to commit). I'll wire the portal URL into the footer with the rest of the staged changes.

## 1. Add the `wiresetweb/wireset-web` repo to this session — BLOCKING (everything ships through this)
**Why:** The new Tools service line is fully built and staged in `wireset-web-changes/`, but my GitHub write access is currently limited to this repo. Once wireset-web is added, I push a review branch there; you merge; Workers Builds auto-deploys it to wiresetweb.com.
**Steps:** In the Claude session/environment settings where you manage repository access (where Fable-Money-Test was granted), add `wiresetweb/wireset-web` too, then tell me "repo added" in chat or here.
**Paste back:** Just confirm it's added. Then my next steps are automatic: branch → apply staged files → you review the PR → merge → verify live.

---

## Completed / obsolete
- ~~Buy domain~~ — already owned (pre-existing business)
- ~~Cloudflare Pages setup~~ — site already live via Worker `wireset-web` + Workers Builds
- ~~Email routing for hello@wiresetweb.com~~ — already live (it's on the site today)

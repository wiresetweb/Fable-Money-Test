# HUMAN TASKS — queue for Laz (newest at top)

Format per task: what, why, exact steps, what to paste back. Credentials go in `.env` (gitignored), never committed.

---

## 3. Pick the contact email for the site — BLOCKING (cheap, do first)
**Why:** The landing page and outreach templates currently use the placeholder `hello@wiresetweb.com`. Every email we send and every site visit needs a real reply address.
**Steps:**
1. Decide the address. Cheapest good option: Cloudflare Email Routing (free) — in the Cloudflare dashboard for wiresetweb.com, go to **Email → Email Routing**, create `hello@wiresetweb.com`, and forward it to lazaroallanes@gmail.com.
2. Send yourself a test email to confirm forwarding works.
**Paste back:** Confirm in this file: "Email routing live, hello@wiresetweb.com → my gmail" (or tell me the different address you chose so I update the site and templates).

## 2. Stripe account + $175 payment link — BLOCKING (Phase 1 gate)
**Why:** We collect 50% of $350 ($175) upfront before building anything for a client. No payment link = no revenue.
**Steps:**
1. Create a Stripe account at stripe.com (sole proprietor / individual is fine to start).
2. Products → Add product: name "Wireset Web — Custom Tool (50% deposit)", price **$175 one-time**.
3. Create a **Payment Link** for it, and a second product/link at **$175** named "...(final 50%)". Two identical-price links keeps bookkeeping clean.
4. Optional but useful: a third link at $350 "paid in full".
**Paste back:** The payment link URLs here (they're public URLs, safe to commit). Anything secret (API keys — not needed yet) goes in `.env`.

## 1. Connect `site/` to Cloudflare Pages on wiresetweb.com — BLOCKING (Phase 1 gate)
**Why:** Gate to Phase 2 is the site live on the domain. The landing page is built and committed at `site/index.html`; demos live at `site/demos/`.
**Steps:**
1. Cloudflare dashboard → **Workers & Pages → Create → Pages → Connect to Git**.
2. Pick this GitHub repo (`wiresetweb/Fable-Money-Test`). If Cloudflare asks for repo access, grant it for this repo only.
3. Build settings: Framework preset **None**, build command **(leave empty)**, build output directory **`site`**. ⚠️ Must be `site`, NOT the repo root — the root contains our internal strategy docs and deploying it would publish them. Production branch: the branch I tell you is current (right now: `claude/wire-set-web-domain-fspbaz`; we'll move to `main` once you've reviewed).
4. After the first deploy, go to the Pages project → **Custom domains → Add** → `wiresetweb.com` (and `www.wiresetweb.com`). Cloudflare auto-creates the DNS records since the zone is already there.
5. Visit https://wiresetweb.com — you should see the Wireset Web landing page, and https://wiresetweb.com/demos/quote-calculator/ should show the demo. Check both on your phone too.
**Paste back:** Confirm "site live at wiresetweb.com" here, plus anything that looked broken on your phone.

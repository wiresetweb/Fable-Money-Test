# Staged changes for `wiresetweb/wireset-web`

This folder mirrors the live site repo's paths. Every file here is a **drop-in
replacement or addition** for the `wiresetweb/wireset-web` repo (the Cloudflare
Worker `wireset-web` auto-deploys from `main` via Workers Builds).

Built from a clone of `main` at commit `f23a746` (2026-05-28) — if `main` has
moved since, diff before applying.

| File here | Action in wireset-web repo |
|-----------|---------------------------|
| `index.html` | **Replace** — adds "Tools" nav + footer links, the `#tools` service-line section (between Pricing and the CTA banner), and a $350 Offer in the JSON-LD. Nothing else touched. |
| `styles.css` | **Replace** — appends `.tools-line` / `.tools-grid` / `.tools-tier` rules before the reduced-motion block. Nothing else touched. |
| `sitemap.xml` | **Replace** — adds `/tools/` entry. |
| `tools/index.html` | **New** — the Custom Tools service page. |
| `demos/tools/quote-calculator/index.html` | **New** — working quote-calculator demo (fictional "Hartline Electric", noindex like other demos). |

Once this session has write access to the wireset-web repo: create a branch
there, apply these files, and open it for Laz's review. Merging to `main`
deploys automatically. Verify after deploy:

1. `wiresetweb.com` — Tools nav link + new section render, nothing else shifted
2. `wiresetweb.com/tools/` — page renders, form posts (Web3Forms)
3. `wiresetweb.com/demos/tools/quote-calculator/` — calculator works on a phone

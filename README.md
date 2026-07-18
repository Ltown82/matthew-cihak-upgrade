# Matthew Cihak Therapy — Website Upgrade Concept

Premium static website concept demo for **Matthew Cihak, LMHC, NCC** (Sioux City, IA). Compares the current SimplePractice brochure site with a conversion-focused private-practice design.

## Live site (GitHub Pages)

**https://ltown82.github.io/matthew-cihak-upgrade/**

### Enable GitHub Pages (one-time, if the URL 404s)

GitHub MCP has no Pages API endpoint, so enable hosting in the repo UI:

1. Open **Settings → Pages** on this repository:  
   https://github.com/Ltown82/matthew-cihak-upgrade/settings/pages
2. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
3. Click **Save**. The site is usually live within 1–2 minutes.

Alternatively, set **Source** to **GitHub Actions** so `.github/workflows/pages.yml` deploys on every push to `main`.

## What's included

- Brand-forward hero and trust messaging
- Gap analysis vs the current live site
- Client journey steps and office hours
- Intent-based service cards
- Insurance / fees block and FAQ
- Feature matrix vs top competitors
- Demo consult request form (client-side only)
- Mobile menu + form success handling (`script.js`)

## Files on `main`

| File | Purpose |
|------|---------|
| `index.html` | Full marketing page (links `styles.css` + `script.js`) |
| `styles.css` | Full design system |
| `styles-a.css` / `styles-b.css` | Split CSS copies (same design) |
| `script.js` | Mobile nav + form demo |
| `.nojekyll` | Disable Jekyll on Pages |
| `.github/workflows/pages.yml` | Optional Actions-based Pages deploy |

## Local preview

Open `index.html` in a browser, or serve the folder with any static file server.

## Notes

This is a **concept demo**, not the official practice site. Public practice details are drawn from [matthewcihak.com](https://www.matthewcihak.com/) and public listings.

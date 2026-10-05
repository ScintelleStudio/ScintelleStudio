# Scintelle Studio website

Quarto site, published with GitHub Pages. Fonts are self-hosted (Outfit, SIL Open Font License), so visitors make no requests to Google.

## Edit
- All page text is in `index.qmd` (search for `CHANGE` and `[PRICE]`).
- Colours and type are at the top of `styles.css`.
- Preview locally: `quarto preview`

## Before launch
- [ ] Replace `hello@scintellestudio.com` with the address you set up (twice in `index.qmd`)
- [ ] Fill in the three `[PRICE]` values and the care plan price
- [ ] Add your photo as `images/ineke.jpg` and swap the placeholder (see comment in `index.qmd`)
- [ ] Say whether prices include VAT, if relevant
- [ ] Check the bisyssla notification with SU, and what you may say about your employer
- [ ] Add a first client site and a testimonial when you have one

## Publish
1. Create a public repository in your GitHub organization and push this folder to `main`.
2. Repository Settings > Pages > Source: **GitHub Actions**.
3. Every push to `main` now rebuilds and publishes the site (`.github/workflows/deploy.yml`).
4. Custom domain: add it under Settings > Pages, set the DNS records at Loopia, then tick "Enforce HTTPS".

Quarto is pinned to one version in the workflow. If you update Quarto locally, update the version number there too.

# Multinational Insurance Brokers (MIB) — Website

Single-page website for Multinational Insurance Brokers, an independent insurance brokerage operating across Africa.

**Live site:** https://www.mibrokers.org/

## What's on the page

- Hero positioning MIB as an independent broker
- Overview of brokerage services
- How we work (three steps) and About, with the CEO profile
- Quote form that opens WhatsApp (0244 519 003) with the enquiry pre-filled; there is no backend and nothing is stored

## Stack

A single `index.html` with inline CSS/JS (Google Fonts: Source Serif 4, Source Sans 3). No build step.

`assets/` holds the MIB logo (`mib-logo.png`, plus a white version for the footer), the favicons and the link-preview image (`og-image.jpg`).

## Run locally

```bash
python3 -m http.server 8000
```

## Deployment

Served by GitHub Pages from `main`. The custom domain is set in `CNAME` (`www.mibrokers.org`) — don't delete that file or the domain will stop resolving to this site.

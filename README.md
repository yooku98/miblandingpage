# Multinational Insurance Brokers (MIB) — Website

Single-page website for Multinational Insurance Brokers, an independent insurance brokerage operating across Africa.

**Live site:** https://www.mibrokers.org/

## What's on the page

- Hero positioning MIB as an independent broker
- Overview of brokerage services
- Contact section (email and WhatsApp)

## Stack

A single `index.html` with inline CSS/JS (Google Fonts: Playfair Display, EB Garamond, Montserrat). No build step.

## Run locally

```bash
python3 -m http.server 8000
```

## Deployment

Served by GitHub Pages from `main`. The custom domain is set in `CNAME` (`www.mibrokers.org`) — don't delete that file or the domain will stop resolving to this site.

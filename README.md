# Gidron Consulting — Responsible AI Review Assistant Website

Landing page for the Responsible AI Review Assistant: plain-language responsible AI reviews for small and mid-size businesses in the U.S. and U.S. territories.

- `public/index.html` — the full landing page
- `netlify/functions/risk-check.mts` — the AI risk quick-check (Netlify Function at `/api/risk-check`, using Claude through Netlify AI Gateway — no API key needed; rate-limited to 5 checks per minute per visitor)
- `netlify.toml` — Netlify deploy settings
- The contact form uses Netlify Forms; submissions appear in the Netlify dashboard under **Forms**.

## Business details
- Business name: Gidron Consulting
- Prices: Starter Review $1,500 · Full Review $3,500 (one-time, fixed)
- Full Review follow-up: 60-minute walkthrough call, follow-up call at 30 days, 30 days of email support
- Contact email: vlgidron@gmail.com

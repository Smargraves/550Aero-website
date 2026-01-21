# 550 Aero — Netlify Site (Investor-Clean)

This is a simple static website (HTML/CSS/JS) designed for fast iteration.

## Deploy to Netlify (fastest)
1. Create a Netlify account.
2. Go to: Sites → Add new site → Deploy manually.
3. Drag-and-drop the ZIP (or the folder contents) into Netlify.

## Connect your domain (550aero.ai)
Netlify: Site configuration → Domain management → Add domain.

If your domain is currently managed at Hostinger, you will either:
- Option A (recommended): Use Netlify DNS (Netlify gives you nameservers to paste into Hostinger).
- Option B: Keep Hostinger DNS and add:
  - A record: apex/root → 75.2.60.5
  - A record: apex/root → 99.83.190.102
  - CNAME: www → <your-netlify-subdomain>.netlify.app

Netlify will show the exact records and verify.

## Updating later
- Manual: drag-and-drop a new ZIP again (Netlify creates a new deploy).
- Optional: connect GitHub for one-click updates.

## Contact form
Uses Netlify Forms. After the first deploy:
Netlify → Forms → you’ll see “briefing” submissions.

---

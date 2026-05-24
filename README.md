# Social Health Systems — Website

The public-facing website for **Social Health Systems (SHs)** — building the infrastructure for human connection.

## Structure

- `index.html` — Main homepage (18 sections, interactive diagnostic, stickiness layer)
- `schools.html` — Schools & Districts landing page
- `enterprise.html` — Enterprise & HR landing page
- `healthcare.html` — Healthcare landing page
- `community.html` — Communities & Families landing page
- `accreditation.html` — SHa Accreditation overview + application
- `contact.html` — Contact form + booking
- `article-dei-to-shs.html` — Article: From DEI to SHs
- `article-360b-problem.html` — Article: The $360B Problem
- `article-herriman.html` — Article: Herriman Case Study

## Setup

1. Push to GitHub
2. Enable GitHub Pages (Settings → Pages → Deploy from branch → main)
3. Replace `YOUR_FORM_ID` in `contact.html` with your [Formspree](https://formspree.io) endpoint
4. Update email address in `contact.html`
5. Add Google Calendar booking link in `contact.html`

## Tech

- Static HTML/CSS/JS — no build step, no framework
- Google Fonts (Inter Tight, Source Serif 4, JetBrains Mono)
- All assets inline (SVG illustrations, base64 photos)
- 272KB total site weight

© 2011–2026 Social Health Systems

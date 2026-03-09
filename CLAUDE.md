# CLAUDE.md

## What This Is
Tooley landing page and lesson plan discovery platform for teachers. Bilingual (EN/ES) static site with lesson galleries and an interactive web-based lesson generator.

## Stack
- HTML/CSS/JS (static, no framework)
- Vanilla JavaScript with client-side routing
- jsPDF (PDF generation via CDN)
- Google Fonts (Inter, Space Grotesk)
- lessons.json (static lesson catalog)

## Hosting
- GitHub Pages (static frontend)
- API backend: tooley-pwa-production.up.railway.app (hardcoded in app.html)

## Env Vars
None. Static site with hardcoded API endpoint.

## Key Files
| File | Purpose |
|------|---------|
| `index.html` / `index-es.html` | Landing pages |
| `app.html` / `app-es.html` | Lesson generator web app |
| `lessons.json` | Static lesson catalog |

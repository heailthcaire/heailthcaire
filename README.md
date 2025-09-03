# HEaiLTHCaiRE Website

Public-facing static site for HEaiLTHCaiRE: human‑centered, intelligent healthcare technology.

## Overview
- Fast, accessible, mobile‑first
- Plain HTML / CSS / (optional) light JS
- Deployed via GitHub Pages
- Goal: Clear value, trust, and scalability for future sections (blog, case studies)

## Brand
Use exact casing: HEaiLTHCaiRE  

## Structure (Example)
````text
index.html
about.html
contact.html
privacy.html
terms.html
/assets
  /css/styles.css
  /js/main.js
  /img/logo.svg
README.md
````

## Local Development
````bash
git clone https://github.com/YOUR_ORG/HEaiLTHCaiRE-website.git
cd HEaiLTHCaiRE-website
python -m http.server 4000
# visit http://localhost:4000
````

## Deployment (GitHub Pages)
1. Repo Settings → Pages → Source: main (root)
2. Wait ~1–2 minutes
3. (Optional) Add custom domain + enforce HTTPS

## Updating
````bash
git add .
git commit -m "Update: refine hero section"
git push
````

## Contributing
Branch naming:
````text
feature/<short-description>
fix/<issue-or-bug>
````

Example:
````bash
git checkout -b feature/team-section
````

Open a Pull Request with a short summary (screenshots if visual).

## Accessibility & Quality
- Semantic HTML (header, nav, main, footer)
- Keyboard-focus visible
- Descriptive meta title + description per page
- Alt text: describe purpose, not “image”
- Keep hero images <250KB when possible

## Roadmap (Lite)
- Core marketing pages (current)
- Blog / Insights
- Case Studies section
- Lightweight privacy-first analytics
- Structured data (schema.org)
- Internationalization (future)

## Contacts
General: contact@heailthcaire.com  
Careers: talent@heailthcaire.com  
Security: security@heailthcaire.com  

## License
Copyright (c) HEaiLTHCaiRE. All rights reserved.

## TL;DR
````bash
clone -> edit -> commit/push -> GitHub Pages auto-deploy
````

(Replace YOUR_ORG, emails, and structure as needed.)

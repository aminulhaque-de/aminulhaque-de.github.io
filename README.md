# Personal Profile — Aminul Haque

A minimal, accessible, and responsive single-page portfolio for a Senior Data Engineer.  
Dark, code-themed design optimized for GitHub Pages — built with semantic HTML5 and a lightweight custom CSS file (no frameworks).

## Contents
- `index.html` — main site
- `assets/css/style.css` — theme and responsive layout
- `README.md` — this file

## Features
- Dark "Data Engineer" aesthetic with monospace/code typography
- Clean, semantic HTML for accessibility and SEO (Open Graph + JSON-LD)
- Responsive layout (mobile-first)
- Fast, dependency-free (no JS frameworks)
- Sections: Hero, Skills, Experience (timeline), Projects, Contact footer

## Quick deploy (GitHub Pages)
1. Ensure files are in your repository root (or the repo root contains `index.html` and `assets/`).
2. Push changes to a branch (example uses `fill-profile`):
   - git add .
   - git commit -m "Add personal profile site"
   - git push origin fill-profile
3. Open a Pull Request from `fill-profile` → `main` and merge.
4. In GitHub: Settings → Pages:
   - Under "Source", select the branch `main` and folder `/ (root)`.
   - Save. The site will publish at `https://<username>.github.io/<repo>/` (may take a minute).

Tip: You can also use the GitHub CLI to create a PR:
- gh pr create --title "Add personal profile site" --body "Add site assets and index.html" --head fill-profile --base main

## Local preview
Preview quickly with a static server from the repo root:

- Python 3:
  - `python -m http.server 8000`
  - Open http://localhost:8000 in your browser

- Node (http-server):
  - `npx http-server -p 8000`
  - Open http://localhost:8000

## Customize
Edit `index.html` to change:
- Name, location, and professional summary (found in the hero and footer)
- Social links (LinkedIn, GitHub, email)
- Projects: update project titles, descriptions, and GitHub repo links

Edit `assets/css/style.css` to tweak colors, spacing, typography, or to self-host fonts.

Optional:
- Add `assets/img/avatar.jpg` and include an `<img>` in the header.
- Add more projects or expand experience entries using the existing card/timeline pattern.

## Accessibility & SEO notes
- The site includes a skip link, semantic sections, and JSON-LD structured data to improve search results.
- Add descriptive alt text for any avatar or project images you include.
- Keep the hero summary concise for better SERP snippets.

## License
MIT — feel free to use and adapt for personal use.

## Contact
Email displayed on the site: ahatremotework@gmail.com

If you want, I can:
- Open the PR for you from `fill-profile` → `main` (confirm and I will create the PR), or
- Make additional edits (add avatar, update project links, tweak copy or styles).
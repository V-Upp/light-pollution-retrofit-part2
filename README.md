# Cobra-Head Retrofit Hood — Documentation Site

Plain HTML/CSS site, no build step required.

## Structure
```
index.html       Home
project.html      Background, objective, constraints
design.html       CAD renders, dimensions, mounting method
research.html     Study topics and open questions
progress.html     Chronological engineering notebook
resources.html    Terminology, standards, tools
contact.html      Contact info
assets/css/style.css
assets/js/main.js       (mobile nav toggle only)
assets/images/          CAD renders + Big Bend photos
```

## Publishing on GitHub Pages
1. Push this folder to a GitHub repo (these files at the repo root, or in `/docs`).
2. In the repo: **Settings → Pages → Build and deployment → Deploy from a branch**.
3. Pick `main` branch, root (or `/docs`) folder, save.
4. Your site will be live at `https://<username>.github.io/<repo-name>/`.

## Editing content
Every page is a plain `.html` file — open it in any text editor and edit the
text directly. Shared styling lives in `assets/css/style.css`; you generally
won't need to touch it to update copy.

## Known placeholders to fill in later
- `design.html`: STEP/STL/SVG/Python file downloads aren't linked yet — add
  them once the CAD files are uploaded to a `/cad` folder in this repo.
- `research.html`: literature review is an outline only, no citations yet.
- `contact.html`: Nabhya's GitHub/LinkedIn links.
- `resources.html`: downloadable PDF proposal + drawing package.

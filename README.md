# Monish | Portfolio

A single-page personal portfolio for Monish, a student developer who builds Android apps, AI and ML systems, and full stack web applications.

**Live site:** https://github.com/monipk

## Overview

The site is one self-contained HTML file with no build step and no framework. It shows selected projects, the tech stack, what I am learning and how to get in touch.

Sections:

- **About:** a short introduction and interests
- **Selected work:** ScamShield, FuelWise, ResumeSync AI, SIH 2026 entry, PHP e-commerce platform, browser automation agent, PostgreSQL login system, Titanic survival API, generated pitch decks and a modulo-3 counter
- **Stack:** languages, frameworks, data, AI and tooling
- **Learning:** what I am currently studying
- **Contact:** email and phone

## Design

- **Typography:** Newsreader for headings and Plus Jakarta Sans for body text, loaded from Google Fonts
- **Palette:** two neutrals and one deep petrol accent, defined as CSS variables at the top of the file
- **Layout:** a sticky left column with identity and contact, and a scrolling content column on the right that collapses to a single column on small screens
- **Theme:** follows the system light or dark setting automatically
- **Motion:** none beyond standard link states, so it stays calm and fast
- **Accessibility:** visible keyboard focus, semantic headings and landmarks, and sufficient color contrast

## Project structure

```
.
├── index.html   # the entire site: markup, styles and content
└── README.md
```

Rename `portfolio.html` to `index.html` before publishing so hosts serve it at the root.

## Run locally

No installation is needed.

```bash
# Option 1: open the file directly
open index.html

# Option 2: serve it locally
python -m http.server 8000
# then visit http://localhost:8000
```

## Customize

1. **Links:** search for `github.com` and `linkedin.com` in `index.html` and replace them with your full profile URLs.
2. **Colors:** edit the variables in `:root` (`--bg`, `--ink`, `--muted`, `--line`, `--accent`) and the matching dark theme values.
3. **Projects:** each project is one `.proj` block. Copy a block, then change the label, title, description and stack line.
4. **Contact:** update the `mailto:` and `tel:` links in both the sidebar and the contact section.

## Deploy

**GitHub Pages**

1. Push `index.html` to a repository.
2. Open **Settings**, then **Pages**.
3. Choose the `main` branch and the root folder, then save.
4. The site goes live at `https://YOUR_USERNAME.github.io/YOUR_REPO/` within a minute or two.

The same file also works on Netlify, Vercel or Cloudflare Pages by dragging the folder in or connecting the repo.

## Tech

HTML, CSS and Google Fonts. No JavaScript, no dependencies.

## Contact

- Email: monipk1604@gmail.com
- Phone: 7538801604
- GitHub: https://github.com/YOUR_USERNAME
- LinkedIn: https://www.linkedin.com/in/YOUR_LINKEDIN_ID

## License

All content and code are copyright Monish. If you like the layout, feel free to take inspiration, but please do not copy the text or project descriptions.

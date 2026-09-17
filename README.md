# Demo Café — Aroma & Co.

Practice repo: responsive café landing page — HTML/CSS layout practice using Flexbox, Grid, and vanilla JavaScript. No CSS framework or build tools.

## Overview

A single-page café concept with a hero, story, menu, opening hours, and location section. The focus is layout, typography, and visual interactions, including an animated SVG coffee cup, hover tilt, a custom cursor, and scroll reveals.

This repository is presented as a practice/demo project, not a verified freelance client case study. The café copy, statistics, and contact details should be treated as demo content, not evidence of a real business engagement.

## Tools and structure

- **HTML5:** page structure and inline SVG artwork.
- **CSS:** Flexbox, Grid, custom properties, keyframe animations, and a responsive breakpoint at 900px.
- **Vanilla JavaScript:** cursor tracking, card tilt, scroll effects, and `IntersectionObserver` reveals.
- **Google Fonts:** Cormorant Garamond and DM Sans (requires internet access; system fallbacks are provided).

All markup, styles, and scripts live in [`index.html`](index.html). No package installation is needed.

## Run locally

Open `index.html` directly in a modern browser, or serve the repository with Python 3:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Demo limitations

- “Reserve a Table” scrolls to the visit section; there is no booking service, form submission, or backend.
- Footer social/contact links are placeholders.
- Navigation links are hidden at the mobile breakpoint; there is no mobile menu.
- Accessibility, reduced-motion behavior, and cross-browser/device testing need further work before production use. Several content reveals depend on JavaScript.
- No automated tests or build pipeline are included.

## Portfolio status

Keep this practice repository unpinned unless it is substantially upgraded. Documentation alone does not make it a client case study.

If a real freelance engagement is confirmed, replace the demo framing with an accurate client brief, scope and role, process notes, and permission-cleared before/after screenshots. Record verified outcomes rather than inventing client history or results.

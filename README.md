# Single Page Portfolio

A modern, minimal single-page portfolio to showcase projects and skills. Responsive, fast, easily customizable, and print/PDF ready.

## Overview

- Single-file (HTML/CSS/JS) or small folder
- Responsive (mobile → desktop)
- Dark / light theme
- Print-friendly (PDF-ready)
- Editable content via HTML or a data file (JSON)

## Features

- Sections: Hero, About, Experience, Education, Skills, Projects, Contact
- Download PDF / Print button
- Color theming with CSS variables
- Lightweight components without heavy dependencies

## Technology

- HTML5, CSS3 (Custom Properties), JavaScript (ES6+)
- Optional tooling: Tailwind, Vite, Parcel for modern workflows

## Quick Start

Open `index.html` in a browser or run a simple local server:

```
# from project root
python3 -m http.server 8080
# or (Node)
npx serve .
```

Then visit: http://localhost:8080

## Customization

- Content: edit `index.html` or `data.json`
- Colors: adjust variables in `:root`
- Fonts: swap Google Fonts link in the head
- Print: tune `@media print` to hide UI elements and optimize layout

## Design Tips

- Limit to 2–3 primary colors
- Prioritize readability (high contrast)
- Showcase projects with concise descriptions and links

## License

MIT — use and modify freely. Add a LICENSE file if needed.

-- GitHub Copilot

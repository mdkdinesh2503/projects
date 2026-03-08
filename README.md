# MDK Projects

A single-page project portfolio showcasing web applications built with JavaScript and API-based backends. Each project card links to live demos (where available) and source code on GitHub.

---

## Project structure

```
projects/
├── index.html          # Main portfolio page (HTML + embedded CSS + JS)
├── images/             # Project thumbnails and favicon
│   ├── Project_Title.png   # Favicon
│   ├── Project_2.jpg       # Student Website
│   ├── Project_3.png       # Profile Card
│   ├── Project_10.png      # API - Angular (Student)
│   ├── Project_11.jpg      # API - Java (Student)
│   ├── Project_12.jpg      # Travel Agency
│   ├── Project_13.jpg      # API - Angular (Travel)
│   └── Project_14.jpg      # E-Commerce
└── README.md
```

---

## Features

- **Single-file setup** — One `index.html` with inline CSS and JavaScript; no build step.
- **Responsive layout** — Breakpoints at 500px, 1000px, and 1240px for mobile, tablet, and desktop.
- **Fixed header** — Sticky header with hover styling; “PROJECTS” title and icon.
- **Project cards** — Grid of cards with thumbnail, title, and View/Code links.
- **Two categories** — “Project Based on Javascript” (front-end) and “Project Based on API” (full-stack).
- **Basic protection** — Right-click and Ctrl key disabled (client-side only).

---

## Projects listed

### Project based on JavaScript

| Project         | Description      | Links                    |
|----------------|------------------|--------------------------|
| Student Website| Student-focused site | View, Code (SMS-V1)   |
| Travel Agency  | Travel-themed site   | View, Code (Travel-V1) |
| E-Commerce     | E-commerce front-end | View, Code (Ecom-V1)  |
| Profile Card   | Profile card UI      | View, Code (profilecard)|

### Project based on API

| Project              | Stack   | Link        |
|----------------------|--------|-------------|
| E-Commerce (API)     | Java   | Code (Ecom-V2) |
| Student Module       | Angular| Code (SMS-V2)  |
| Student Module       | Java   | Code (SMS-V3)  |
| Travel Module        | Angular| Code (Travel-V2)|

---

## Tech stack

- **HTML5** — Semantic structure, favicon, viewport meta.
- **CSS3** — Custom properties (variables), Flexbox, media queries, transitions.
- **JavaScript (vanilla)** — Sticky header, scroll behavior, input restrictions.
- **Font Awesome 5.15.3** — Icons (CDN).
- **External links** — GitHub Pages (demos) and GitHub repos (code).

---

## Design

- **Colors** — Brown (`#414141`), light brown (`#b2a9a9`), white; brown/white hover states.
- **Typography** — Verdana, Geneva, Tahoma, sans-serif.
- **Layout** — Centered header; card grid with gap; responsive image sizing.
- **Interactions** — Header and card hover effects; custom scrollbar (brown thumb).

---

## How to run

1. Clone or download the repo.
2. Open `index.html` in a browser (double-click or use a local server).
3. For local server (optional):  
   `npx serve .` or `python -m http.server` from the project root.

No install or build is required.

---

## Browser support

Works in modern browsers that support CSS custom properties, Flexbox, and ES5+ JavaScript. Best tested in Chrome, Firefox, Edge, and Safari.

---

## License and credits

© 2023, All rights reserved by **DINESH KUMAR.M**

---

## File overview

| File / folder | Purpose |
|---------------|--------|
| `index.html` | Full page: structure, styles (~350 lines CSS), and scripts (~15 lines JS). |
| `images/`    | Thumbnails for each project and `Project_Title.png` favicon. |

No package manager, config files, or separate CSS/JS files are used; the site is self-contained in `index.html` and the `images/` folder.

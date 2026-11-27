# Dipika Bhajipale — Portfolio

A responsive, single-page developer portfolio for Dipika Prakash Bhajipale, built with semantic HTML, CSS, and vanilla JavaScript. The site presents her profile, technical toolkit, projects, education, certifications, and contact links without requiring a framework or build process.

## Live site

- Repository: https://github.com/dipika-bhajipale/dipikabhajipale
- Email: dipikabhajipale1012@gmail.com

## Features

- Dark, technical/editorial visual design
- Responsive desktop and mobile navigation
- Loading/boot screen and scroll progress indicator
- Intersection-based reveal animations
- Active navigation highlighting based on the visible section
- About, skills, projects, journey, and contact sections
- Downloadable resume
- Keyboard-friendly navigation, skip link, and reduced-motion support
- CSS-generated project artwork rather than external image assets

## Project structure

```text
.
├── index.html                         # Page structure and content
├── styles.css                         # Layout, visual design, and responsive styles
├── script.js                          # Navigation, boot screen, reveal, and scroll behavior
├── favicon.svg                        # Site favicon
├── Dipika-Bhajipale-Resume.pdf        # Downloadable resume
└── README.md
```

## Run locally

No dependencies or build step are required.

```bash
git clone https://github.com/dipika-bhajipale/dipikabhajipale.git
cd dipikabhajipale
python -m http.server 8000
```

Then open http://localhost:8000 in a browser.

You can also open `index.html` directly, although a local HTTP server is recommended.

## Technology

- HTML5 — page structure and accessible navigation
- CSS3 — responsive layouts, animations, and project visuals
- JavaScript — menu interactions, reveal effects, section tracking, and scroll progress
- Google Fonts — Space Grotesk and DM Mono

## Accessibility

The page includes a skip-to-content link, semantic sections and landmarks, visible keyboard focus, `aria-expanded` and `aria-current` state, Escape-to-close menu behavior, and a `prefers-reduced-motion` fallback.

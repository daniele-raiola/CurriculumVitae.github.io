# Daniele Raiola — Academic Portfolio

A clean, minimal academic portfolio showcasing research in Philosophy of Science, Epistemology, and Scientific Collaboration.

## Overview

This is a **single-page HTML/CSS portfolio** with dark-mode support, designed for fast load times and excellent accessibility. The site features:

- **Responsive design** — Optimized for desktop, tablet, and mobile
- **Dark mode support** — Respects system `prefers-color-scheme` preference
- **Smooth scroll navigation** — Vanilla JavaScript for semantic navigation
- **Semantic HTML** — Properly structured content for accessibility and SEO
- **Zero dependencies** — Pure HTML, CSS, and minimal vanilla JS

## 📋 Sections

1. **About** — Professional profile and specializations
2. **Education** — Master's and Bachelor's degrees with thesis information
3. **Work & Volunteering** — Professional roles and volunteer experience
4. **Skills** — Research, communication, technical, and organizational skills
5. **Conferences & Seminars & Lectures** — Speaking engagements and active participation
6. **Academic References** — Advisor and supervisor contacts
7. **Certificates** — Professional credentials and badges
8. **Contact** — Email, phone, and location information

## 🚀 Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your browser
3. No build process, no dependencies — just open and view!

```bash
# Optional: Use a local server (Python)
python -m http.server 8000
# Visit http://localhost:8000
```

### Customization

Edit `index.html` to update content and structure. All styling is in `styles/main.css`.

#### CSS Variables (Dark/Light Mode)

The portfolio uses CSS custom properties for theming. To modify colors, edit the `:root` variables in `styles/main.css`:

```css
:root {
    --color-bg: #0d1117;           /* Background */
    --color-text: #e0e0e0;         /* Main text */
    --color-accent: #58a6ff;       /* Links & highlights */
    --color-text-secondary: #a0a0a0; /* Secondary text */
    --color-border: #30363d;       /* Borders */
}
```

For light mode, modify the `@media (prefers-color-scheme: light)` block.

## 🌐 GitHub Pages Deployment

This portfolio is hosted on **GitHub Pages** using the `gh-pages` branch or main branch (if configured in repo settings).

### Setup

1. Push code to your GitHub repository
2. Go to **Settings** → **Pages**
3. Set source to `main` branch (or `gh-pages`)
4. Your site will be live at `https://yourusername.github.io/PorfolioDanieleRaiola.github.io/`

Or, if the repository is named `yourusername.github.io`, it will be live at `https://yourusername.github.io/`

## 📱 Responsive Breakpoints

- **Desktop**: Default layout
- **Tablet** (≤768px): Adjusted navigation and skill grid
- **Mobile** (≤480px): Single-column layout, smaller fonts

## ♿ Accessibility

- Semantic HTML5 elements
- Proper heading hierarchy (h1 → h2 → h3)
- Color contrast compliant with WCAG standards
- Keyboard navigation (all links and nav items focusable)
- Smooth scroll behavior with JavaScript fallback

## 🎨 Design Philosophy

This portfolio prioritizes **clarity and accessibility** over visual complexity:

- Minimal animations (fade-in on hover/scroll)
- Clean typography using system fonts
- Dark mode as primary with light mode support
- Content-focused design (academic work is the focal point)

Inspired by academic portfolios like those of [Kai von Fintel](https://kaivonfintel.org/) (MIT Linguist) and [Justin Khoo](https://justinkhoo.com/) (MIT Philosopher).

## 📄 License

© 2025 Daniele Raiola. All rights reserved.

## 📞 Contact

- **Email**: [daniele.raiola98@gmail.com](mailto:daniele.raiola98@gmail.com)
- **Phone**: [+39 331 7171686](tel:+393317171686)
- **Location**: Varese, Italy

---

**Last updated**: April 2026

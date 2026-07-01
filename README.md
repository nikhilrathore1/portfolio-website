# Nikhil Rathore — Portfolio

My personal developer portfolio — a responsive, single-page site with dark/light theming, scroll animations, project showcase with category filtering, and a working contact form.

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Font_Awesome-528DD7?style=flat&logo=fontawesome&logoColor=white" alt="Font Awesome">
  <img src="https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white" alt="Netlify">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat" alt="License">
</p>

> **Live Site:** [nikhil-portfolio.netlify.app](https://nikhil-portfolio.netlify.app/)

## Features

- **Dark / Light theme** — toggle with smooth transition, persists via `localStorage`.
- **Scroll animations** — elements reveal on scroll with staggered timing.
- **Project cards** — loaded from `projects.json`, filterable by category, with live-demo and GitHub links.
- **Contact form** — powered by Netlify Forms; redirects to a custom thank-you page.
- **Responsive** — mobile-first layout with a hamburger menu and fluid typography.
- **SEO & sharing** — Open Graph + Twitter Card meta tags, JSON-LD structured data, semantic HTML.

## Tech Stack

| Layer | Tools |
|-------|-------|
| Markup | HTML5, semantic elements |
| Styling | Vanilla CSS (~3 600 lines), CSS custom properties, media queries |
| Scripting | Vanilla JavaScript (ES6+), Intersection Observer, Fetch API |
| Icons & Fonts | Font Awesome 6, Google Fonts (Poppins) |
| Forms | Netlify Forms |
| Hosting | Netlify |

## Run Locally

No build step — just open the file:

```bash
git clone https://github.com/nikhilrathore1/portfolio-website.git
cd portfolio-website
# open index.html in your browser, or use a local server:
npx serve .
```

## Project Structure

```
.
├── index.html              # Main page
├── thank-you.html          # Contact-form success page
├── assets/
│   ├── config/
│   │   └── projects.json   # Project data (titles, links, tech)
│   ├── css/
│   │   └── style.css       # All styles
│   ├── js/
│   │   └── script.js       # All logic (theme, scroll, projects, form)
│   ├── ele/                # Logos, SVGs, preview image
│   └── projects/           # Project screenshots
└── LICENSE
```

## License

[MIT](LICENSE)

---

Built by [Nikhil Rathore](https://github.com/nikhilrathore1)

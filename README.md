# Sahil Fayaz — Portfolio

A personal portfolio website built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages. It features a custom, fully responsive **"Dark Knight"** theme — deep blacks, gunmetal panels, and a restrained bat-signal gold accent — designed to read as professional first.

<p>
  <img alt="Jekyll" src="https://img.shields.io/badge/Jekyll-CC0000?logo=jekyll&logoColor=white">
  <img alt="GitHub Pages" src="https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=white">
  <img alt="SCSS" src="https://img.shields.io/badge/SCSS-CC6699?logo=sass&logoColor=white">
  <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg">
</p>

**Live site:** https://sahilf.github.io/Github-Portfolio/

---

## Overview

A single-page portfolio that presents my background, experience, projects, and education, plus a dedicated long-form projects page. It is intentionally lightweight — static HTML/SCSS with a small amount of vanilla JavaScript, no front-end framework or build step beyond Jekyll.

### Highlights

- **Custom theme** — hand-written SCSS with CSS-variable design tokens for color, spacing, and typography
- **Responsive** — adapts cleanly from large desktops down to mobile, with a collapsible navigation menu
- **Sticky navigation** — transparent over the hero, condenses to a solid bar on scroll, with scroll-spy active states
- **Subtle motion** — reveal-on-scroll animations that respect `prefers-reduced-motion`
- **SEO-ready** — meta tags via `jekyll-seo-tag` and an auto-generated `sitemap.xml`
- **Custom favicon** — gold bat emblem on a dark tile, with an Apple touch icon

---

## Tech Stack

| Area        | Tooling                                            |
| ----------- | -------------------------------------------------- |
| Generator   | Jekyll (static site generator)                     |
| Hosting     | GitHub Pages (`github-pages` gem)                  |
| Styling     | SCSS                                               |
| Typography  | Oswald (display) + Inter (body), via Google Fonts  |
| Plugins     | `jekyll-seo-tag`, `jekyll-sitemap`                 |

---

## Project Structure

```
portfolio/
├── _layouts/
│   └── default.html      # Base layout: <head>, SEO, fonts, favicon, nav shell
├── assets/
│   ├── css/
│   │   └── style.scss    # Full custom "Dark Knight" theme
│   └── img/              # Bat emblem logos + favicons
├── _config.yml           # Jekyll & SEO configuration
├── index.html            # Single-page portfolio (all sections)
├── projects.md           # Detailed projects page (/projects/)
├── Gemfile               # Ruby dependencies
└── README.md
```

---

## Getting Started

### Prerequisites

- Ruby 2.7 or higher
- [Bundler](https://bundler.io/) (`gem install bundler`)

### Run locally

```bash
# 1. Install dependencies
bundle install

# 2. Start the dev server with live reload
bundle exec jekyll serve --livereload

# 3. Open the site
#    http://localhost:4000
```

> Changes to `_config.yml` require a server restart; all other files reload automatically.

---

## Deployment

The site deploys automatically via **GitHub Pages**. Push to the default branch and GitHub builds and publishes the site using the `github-pages` gem — no separate CI step required.

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

To configure: open the repository's **Settings → Pages** and set the source branch.

---

## Customization

| What                | Where                                                       |
| ------------------- | ----------------------------------------------------------- |
| Page content        | `index.html` (sections) and `projects.md` (projects page)   |
| Site metadata & SEO | `_config.yml`                                               |
| Colors & typography | CSS variables in the `:root` block of `assets/css/style.scss` |
| Logos & favicons    | `assets/img/`                                               |

The color scheme is driven by a small set of tokens — adjust these to re-skin the entire site:

```scss
:root {
  --bg:   #0a0b0d;   /* base background */
  --ink:  #eceef2;   /* primary text   */
  --gold: #ffce3a;   /* accent          */
}
```

---

## License

Released under the [MIT License](https://opensource.org/licenses/MIT). Content and personal information remain © Sahil Fayaz.

---

## Contact

- **Email:** sahil.fayaz8899@gmail.com
- **LinkedIn:** [linkedin.com/in/sahil-f](https://www.linkedin.com/in/sahil-f/)
- **GitHub:** [github.com/sahilf](https://github.com/sahilf)

# Amanda Ahanonu — Portfolio

Live Site (GitHub Pages): https://mandss1972.github.io/Amanda-Portfolio-Assignment1-/
Public Repo: https://github.com/Mandss1972/Amanda-Portfolio-Assignment1-

## Overview
A 4-page portfolio (**Home, About, Projects, Contact**) built with semantic HTML and a responsive, fluid layout using **floats + media queries**. **No flexbox** is used anywhere (per course rules).

## Viewports (Fluid + Media Queries)
- **Mobile:** 0–599px → `styles-mobile.css` (single column, fluid widths)
- **Tablet:** 600–991px → `styles-tablet.css` (typography/spacing tweaks)
- **Laptop/Desktop:** ≥992px → `styles-desktop.css` (float-based two-column layout)

**Rationale:** Breakpoints reflect common device widths. The wrapper uses percentage widths with a max-width for readability. Desktop uses floats (plus a clearfix) to satisfy the “no flexbox” requirement.

## Gradients (Where I used them)
- **Linear (180°)** — Home page hero:  
  `.hero { background: linear-gradient(180deg, #ffe3f1, #ffffff); }`
- **Angled linear (135°)** — Footer strip on all pages:  
  `.footer-strip { background: linear-gradient(135deg, #ffd1e8, #e3f0ff); }`
- *(Optional, if you added it)* **Linear (180°)** — About page “About Menu” card:  
  `.box.pink-box { background: linear-gradient(180deg, #ffe3f1, #fff0f7); }`

## Color Scheme (Adobe Color)
Palette selected via https://color.adobe.com/create  
- **Text:** `#0f172a`  
- **Accent (buttons):** `#ec4899`  
- **Links/Focus:** `#1d4ed8`  
- **Gradient colors:** `#ffe3f1`, `#ffd1e8`, `#e3f0ff`, `#ffffff`

(Implemented as CSS variables in `styles-mobile.css` for consistency.)

## Accessibility
- Meaningful alt text for images (e.g., About page headshot)
- Keyboard focus outlines retained
- Sufficient color contrast verified with WAVE
- Semantic landmarks: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`

## External Code (≤10%)
This site is built from **lecture patterns**. Any non-lecture snippet added later will:
1) be ≤10% of total code,  
2) include inline comments explaining its function, and  
3) be cited here with author + link.

_Currently: no external snippets beyond lectures._

## Validation (on the live URL)
- W3C **HTML** Validator (each page)  
- W3C **CSS** Validator (each stylesheet)  
- W3C **Link** Checker (site-wide)  
- **WAVE** Accessibility  
- Spell-check (editor)

## How to Run Locally
Open `index.html` in a browser.  
Assets are in `images/` and `video/` (About page uses `images/me.png` and `video/intrvid.mp4`).

## Version Control / Hosting
- Repository is **Public** (private repos receive 0 for version control per instructions).  
- Deployed via **GitHub Pages** from the `main` branch, `/root` folder.

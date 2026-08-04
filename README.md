# My Portfolio

A single-page, fully responsive portfolio website. Builds on a previous plain-HTML project by adding CSS styling — Flexbox layout, media queries, the box model, custom typography, and a dark mode toggle powered by CSS variables and a small bit of JavaScript.

https://roadmap.sh/projects/portfolio-website

## Repository

[https://github.com/jcgfacurib/website](https://github.com/jcgfacurib/website)

## Live Page

[https://jcgfacurib.github.io/website/home.html](https://jcgfacurib.github.io/website/home.html)

Project URL: https://jcgfacurib.github.io/website/home.html

## Features

- Responsive layout built with **Flexbox** (header, three-column section, review cards)
- **Media queries** for mobile: columns and cards stack vertically, nav bar switches to a vertical layout below 768px
- Consistent use of the **box model** (`box-sizing: border-box`, padding, borders) throughout
- A styled, responsive **contact form** with labeled inputs and focus states
- **Google Fonts** — Inter for body text, Space Mono for the main heading
- **Dark mode** toggle using CSS custom properties (variables) and vanilla JavaScript — no page reload, colors switch instantly

## How to Run Locally

No installation or build step needed — it's static HTML, CSS, and a few lines of JS.

1. Download or clone this repository
2. Make sure `home.html` and `style.css` are in the same folder
3. Double-click `home.html`, or drag it into any web browser (Chrome, Firefox, Edge, Safari)
4. An internet connection is needed on first load so the Google Fonts can be fetched

## How to Publish on GitHub Pages

1. Push this repository to GitHub (already done: [jcgfacurib/website](https://github.com/jcgfacurib/website))
2. In the repo, go to **Settings → Pages**
3. Under "Branch," select `main` and folder `/ (root)`, then click **Save**
4. Wait a minute, then the page is live at:
   `https://jcgfacurib.github.io/website/home.html`

## Project Structure

```
website/
├── home.html    # Page structure and content
├── style.css    # All styling: layout, typography, color variables, dark mode, media queries
└── README.md    # This file
```

## Notes

This project focuses on core CSS techniques: Flexbox for layout, media queries for responsiveness, the box model for consistent spacing, and CSS custom properties (`--variable-name`) to drive a theme system. The dark mode toggle swaps a `data-theme="dark"` attribute on the `<html>` element via JavaScript, which activates an alternate set of color variables defined in `style.css` — every element that reads from those variables updates automatically with no duplicated CSS.

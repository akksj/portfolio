# Sarthak Giri · Portfolio

Personal portfolio of Sarthak Giri, Full Stack Developer (MERN, PHP/MySQL).

**Live:** https://akksj.github.io/portfolio/

A single-page site in plain HTML, CSS and vanilla JavaScript. There's no build step, so GitHub Pages serves it straight from `main` (root).

## Structure

```
index.html            page content, SEO and Open Graph meta
assets/css/style.css  styles (responsive, dark theme)
assets/js/main.js     mobile nav, scroll reveal, language bar (static data)
assets/img/favicon.svg
```

## Edit

- Projects, skills and timeline live in `index.html`.
- GitHub language stats are static, in the `LANGUAGES` array in `assets/js/main.js` (snapshot from 16 Oct 2026).
- LinkedIn and email buttons are hidden placeholders in the Contact section. Set their `href` and remove `hidden` to show them.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

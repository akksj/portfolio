# Sarthak Giri · Portfolio

Personal portfolio of Sarthak Giri, Full Stack Developer (MERN, PHP/MySQL).

**Live:** https://akksj.github.io/portfolio/

A single-page, chapter-by-chapter scroll story in plain HTML, CSS and JavaScript: intro, the problem, projects as pinned scenes, a skills orbit, a journey timeline and a contact finale. A WebGL aurora and a particle field react to the mouse. Motion uses GSAP 3.13.0 + ScrollTrigger and Lenis 1.3.27 from jsDelivr (pinned versions with SRI). There's no build step. If the CDN fails, JS is off, or the visitor prefers reduced motion, the page shows everything statically.

## Structure

```
index.html            page content, SEO and Open Graph meta
assets/css/style.css  styles (dark neon theme, glass cards, responsive, reduced-motion rules)
assets/js/main.js     WebGL aurora, particles, cursor, GSAP/Lenis scroll story, language bar (static data)
assets/img/favicon.svg
```

## Edit

- Projects, skills and timeline live in `index.html`.
- GitHub language stats are static, in the `LANGUAGES` array in `assets/js/main.js` (snapshot from 16 Oct 2026).
- The email button in the Contact section is a hidden placeholder. Set its `href` and remove `hidden` to show it.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

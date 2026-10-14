# Emiliano Zorn — Personal Website

Personal portfolio of Emiliano Zorn, Head of Training at Wazuh. Published with GitHub Pages at [emilianozorn.com](https://emilianozorn.com).

## Stack

Static single-page site: plain HTML, CSS and vanilla JavaScript. No build step or dependencies.

- `index.html` — all content (Home, About, Experience, Skills, Education, Contact)
- `assets/css/styles.css` — styles (BEM naming, CSS variables, mobile first, light/dark theme)
- `assets/js/main.js` — mobile menu, active link on scroll, theme toggle
- `assets/img/` — profile images
- `assets/pdf/emilianozorn-cv.pdf` — CV served by the "Download CV" button

Fonts (Inter) and icons (Unicons) are loaded from CDN.

## Local preview

Open `index.html` in a browser, or run `python -m http.server` in the repo root.

## Updating the CV

Replace `assets/pdf/emilianozorn-cv.pdf`, keeping the file name.

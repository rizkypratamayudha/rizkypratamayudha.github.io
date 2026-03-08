# Portfolio Website

A static HTML/CSS/JS personal portfolio website for Rizky Pratama Yudha.

## Project Structure

- `index.html` — Main portfolio page
- `style.css` — Stylesheet
- `script.js` — JavaScript for interactivity and animations
- `assets/` — Images, icons, and CV PDF

## Tech Stack

- Pure HTML5, CSS3, JavaScript (no build step)
- AOS (Animate On Scroll) via CDN
- Font Awesome icons via CDN

## Running the Project

The site is served statically using the `serve` package:

```
serve . -l 5000
```

## Deployment

Configured as a **static** deployment with `publicDir: "."`.

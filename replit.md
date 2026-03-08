# Portfolio Website

A fully responsive personal portfolio website for Rizky Pratama Yudha showcasing projects, skills, and experience.

## Features

- **Fully Responsive Design** - Optimized for all screen sizes from mobile (480px) to large desktops (1400px+)
- **Mobile Navigation** - Hamburger menu for smaller screens
- **Smooth Animations** - AOS (Animate On Scroll) integration for engaging effects
- **Modern Layout** - Professional grid-based layout using CSS Grid and Flexbox
- **Fast Loading** - Pure static HTML/CSS/JS with no build step needed

## Project Structure

- `index.html` — Main portfolio page with all sections
- `style.css` — Comprehensive responsive stylesheet with media queries
- `script.js` — Mobile menu toggle functionality
- `assets/` — Images, icons, and CV PDF

## Tech Stack

- HTML5, CSS3, JavaScript (vanilla, no frameworks)
- AOS (Animate On Scroll) via CDN
- Font Awesome icons via CDN
- BoxIcons for social media icons

## Running the Project

The site is served statically using the `serve` package:

```bash
serve . -l 5000
```

## Responsive Design Features

### Breakpoints & Adaptations
- **1200px+**: Desktop layout with full navigation and multi-column grids
- **1024px**: Hamburger menu activation, tablet-friendly adjustments
- **768px**: Single-column layouts, adjusted skill and project grids
- **480px**: Mobile-optimized UI with compact spacing and touch-friendly buttons

### Key Responsive Elements
- **Header**: Font sizes scale with `clamp()`, logo auto-sizes
- **Hero Section**: SVG title scales responsively, heading text adapts
- **About Section**: Profile image and text stack on mobile, side-by-side on desktop
- **Skills Grid**: Auto-fit layout from 6 columns (desktop) to 2-3 columns (mobile)
- **Projects Grid**: 3 columns on desktop, 1 column on mobile with proper spacing
- **Footer**: Flexible grid layout that reflows for all screen sizes

### Responsive Features
- Flexible `padding` and margins using `rem` units
- `clamp()` for fluid font sizing (scales between min/max without breakpoints)
- `aspect-ratio` for maintaining image proportions
- `grid-template-columns: auto-fit` for automatic wrapping
- `object-fit` for proper image scaling
- Touch-friendly button sizes on mobile

## Deployment

Configured as a **static** deployment with `publicDir: "."`.

### Deploy to Production
Click the "Publish" button in the Replit interface to deploy the site to the public web.

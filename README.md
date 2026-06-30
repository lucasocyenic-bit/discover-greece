<![CDATA[# 🏛️ Discover Greece

> *Where mythology meets paradise* — a luxury, single-page travel experience built entirely with vanilla JS, GSAP, Three.js, and Lenis.

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Site-D4AF37?style=for-the-badge)](https://lucasocyenic-bit.github.io/discover-greece/)

## ✨ Overview

Discover Greece is a high-end, animation-driven concept site for a luxury travel brand. It blends classical Greek aesthetics — marble, gold, deep navy and aegean blues — with modern interaction design: a custom cursor, magnetic buttons, 3D tilt cards, and a WebGL water shader in the hero.

## 🛠️ Tech Stack

- **Vanilla HTML / CSS / JS** — no framework, no build step
- **[GSAP](https://gsap.com/) + ScrollTrigger** — scroll-driven reveals, parallax, and entrance animations
- **[Three.js](https://threejs.org/)** — custom shader-based animated water/particle scene in the hero
- **[Lenis](https://lenis.darkroom.engineering/)** — buttery smooth scrolling
- **Google Fonts** — Playfair Display, Cormorant Garamond, Inter

## 🎨 Features

- Custom animated cursor with hover and ripple effects (disabled automatically on touch devices)
- Three.js shader-based hero water scene with mouse-reactive waves
- GSAP scroll-triggered reveals across every section
- 3D tilt effect on destination cards
- Magnetic buttons
- Horizontally scrollable beach gallery with scroll-snap
- Interactive travel planner form
- FAQ accordion
- Hidden Konami code easter egg 🎮 (try ↑ ↑ ↓ ↓ ← → ← → B A)
- Fully responsive, down to mobile
- Respects `prefers-reduced-motion` for accessibility
- Graceful `<noscript>` fallback

## 📂 Structure

This is a single self-contained `index.html` file (HTML + CSS + JS), making it trivially easy to preview, fork, or deploy anywhere static files are served.

## 🚀 Running locally

No build step required — just open `index.html` in a browser, or serve it locally:

```bash
npx serve .
```

## 📄 License

This is a personal/portfolio project. Imagery is sourced from [Unsplash](https://unsplash.com).
]]>
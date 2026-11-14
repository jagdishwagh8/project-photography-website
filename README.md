# Mono Studio — Photography Studio Website

A minimal, fully responsive five-page website for a fictional photography studio,
built with pure HTML and CSS. No build tools, no frameworks, no dependencies —
just clean, semantic markup and a single stylesheet.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-b8783c)
![License](https://img.shields.io/badge/License-MIT-767676)

---

## Overview

**Mono Studio** is a photography studio site designed around the idea of
*presence over posing* — honest light, an unhurried process, and pictures that
feel like the person in them. The website mirrors that philosophy: restrained
typography, generous whitespace, and a four-colour palette that keeps the
photography front and centre.

The project is a complete, production-ready static site that can be dropped onto
any host (GitHub Pages, Netlify, Vercel, or a plain web server) without a build step.

---

## Pages

| Page | File | Purpose |
|---|---|---|
| **Home** | `index.html` | Hero, studio approach, four-step process, FAQ, final enquiry CTA |
| **About** | `about.html` | Studio story, principles, how we work, closing CTA |
| **Services** | `services.html` | Six service cards, process grid, considerations, panel CTA |
| **Projects** | `portfolio.html` | Filterable grid of six shoots (Portraits, Editorial, Product, Spaces) |
| **Contact** | `contact.html` | Studio details, working hours, and a full enquiry form |

---

## Features

- **Five fully responsive pages** — designed and tested from 380 px to 1440 px and beyond
- **4-colour palette** — white, black, grey, and a single warm amber accent
- **Filterable project grid** — filter by shoot type with a live project count
- **Single shared stylesheet** — every page uses the same `style.css`, built with CSS custom properties
- **Mobile-first navigation** — CSS-only hamburger menu, no JavaScript required for the nav
- **Accessible by default** — semantic landmarks, visible focus states, `prefers-reduced-motion` support, descriptive `alt` text
- **No dependencies** — no jQuery, no Bootstrap, no build step; just open `index.html`
- **Printable enquiry form** — the contact form is fully structured with labelled fields, autocomplete hints, and native validation

---

## Tech Stack

- **HTML5** — semantic markup with ARIA labels where appropriate
- **CSS3** — custom properties (variables), Grid, Flexbox, clamp() for fluid type and spacing
- **Vanilla JavaScript** — ~20 lines, used only for the portfolio filter on `portfolio.html`

---

## Colour Palette

The entire site uses **exactly four base colours**:

| Swatch | Name | Hex | Usage |
|---|---|---|---|
| ⬜ | White | `#ffffff` | Backgrounds, cards, inverse text |
| ⬛ | Black | `#161616` | Body text, dark sections, borders |
| ◼️ | Grey | `#767676` | Secondary text, muted labels |
| 🟧 | Amber | `#b8783c` | Accent — buttons, links, active states, focus outlines |

All other tones (borders, hover surfaces, inverse text) are derived from these
four using `rgba()` opacity — no additional colours are introduced.

---

## Typography

| Role | Family | Sizes |
|---|---|---|
| Headings (H1, H2) | Iowan Old Style / Palatino / Georgia (serif) | `clamp(42px, 6vw, 76px)` → `clamp(32px, 4.5vw, 52px)` |
| Headings (H3) & body | Helvetica Neue / Arial (sans-serif) | `clamp(18px, 2.2vw, 24px)` → `14–15px` |
| Micro / labels | Same sans-serif | `10–12px`, uppercase, letter-spaced |

Spacing follows an 8 px scale: `8 · 16 · 24 · 40 · 64 · 96`.

---

## File Structure

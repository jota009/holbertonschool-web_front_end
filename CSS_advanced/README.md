# Advanced CSS Project

Welcome to the **Advanced CSS** project! This repository contains a step-by-step build of a modern, component-based homepage style using CSS features such as custom properties (variables), pseudo-classes and elements, responsive layout utilities, and animations.

---

## 📂 Directory Structure

```
CSS_advanced/
├── README.md
├── index.html
├── styles/
│   ├── 1-style.css    # Smooth scrolling & base defaults
│   ├── 2-style.css    # Color palette & visually-hidden utility
│   ├── 3-style.css    # Custom properties: colors & text
│   ├── 4-style.css    # Custom properties: fonts & headings
│   ├── 5-style.css    # Custom properties: font sizes & html scaling
│   ├── 6-style.css    # Google Fonts integration
│   ├── 7-style.css    # Font-family updates
│   ├── 8-style.css    # Line-height declarations
│   ├── 9-style.css    # Anchor reset
│   ├── 10-style.css   # Section header alignment
│   ├── 11-style.css   # Tagline text transform & weight
│   ├── 12-style.css   # Section title styling
│   ├── 13-style.css   # Link pseudo‑states (visited, hover, active)
│   ├── 14-style.css   # Normalize.css import
│   ├── 15-style.css   # Universal box-sizing rule
│   ├── 16-style.css   # Centered fixed‑width container
│   ├── 17-style.css   # Section & footer padding utilities
│   ├── 18-style.css   # Navigation bar & nav‑item styling
│   ├── 19-style.css   # Grid utilities & column classes
│   ├── 20-style.css   # Row clearfix pseudo‑element
│   ├── 21-style.css   # Consolidated column selector
│   ├── 22-style.css   # Dark theme overrides
│   ├── 23-style.css   # Footer & social link styling
│   ├── 24-style.css   # Card‑services block links
│   ├── 25-style.css   # Button component styling
│   ├── 26-style.css   # Testimonial component styling
│   ├── 27-style.css   # Hero section background & spacing
│   ├── 28-style.css   # Header & logo positioning
│   ├── 29-style.css   # Navigation pseudo‑element hover effect
│   ├── 30-style.css   # Card‑work image reveal & overlay
│   ├── 31-style.css   # Testimonial quote animation
│   └── 32-style.css   # Final transforms & transitions
├── images/           # All required high‑res and logo images
└── favicon.jpg, logo-*.png
```

---

## 🚀 Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/holbertonschool-web_front_end.git
   cd holbertonschool-web_front_end/CSS_advanced
   ```
2. **Open** `index.html` in your browser (Chrome v78+).
3. **Link** the desired stylesheet in the `<head>`:

   ```html
   <link rel="stylesheet" href="styles/32-style.css">
   ```
4. **Enjoy** the fully styled homepage with modern CSS techniques!

---

## 🎯 Key Features & Techniques

* **CSS Custom Properties** for colors, typography, spacing, and transitions
* **Responsive grid utilities** (`.row`, `.col-1-2`, `.col-1-3`, `[class^="col-"]`)
* **Pseudo‑classes & elements** (hover, visited, active, `::before`, `::after`)
* **Reset & normalize** using `normalize.css` and universal `box-sizing`
* **Componentized styling** for header, nav, buttons, cards, hero, and testimonials
* **Smooth scrolling** with `scroll-behavior`
* **Animations & transitions** via CSS variables and shorthand syntax
* **Dark theme** overrides using data attributes (`[data-section-theme="dark"]`)

---

## 📝 How It Was Built

Each `N-style.css` file builds incrementally on the previous:

1. **1-style.css** — Basic resets and smooth scrolling
2. **2–5** — Define color, font, and size scales with custom properties
3. **6–9** — Integrate Google Fonts, line-height, and clean anchor styles
4. **10–17** — Section, container, grid, footer, and dark theme layout rules
5. **18–21** — Navigation and column abstraction enhancements
6. **22–24** — Theme overrides, footer, cards, and buttons
7. **25–31** — Hero, header, card reveals, testimonial quotes, and quotes animation
8. **32-style.css** — Final interactive transforms and transitions

---

## 💡 Tips for Future Work

* **Responsive Design**: Next project will reuse these high‑res images for breakpoints
* **Accessibility**: Continue enhancing with `aria-` attributes and focus states
* **Performance**: Consider critical‑path CSS extraction and minification

---

## 📜 Authors

* **Josniel Ramos** – Front‑End CSS Developer
* **Project Team** – Holberton School Web Front‑End

---

© 2025 Holberton School. All rights reserved.

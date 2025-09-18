 # Responsive Website Starter (HTML + CSS)
 
 A minimal, production-ready starter for a responsive, accessible website using only HTML and CSS.
 
 ## Quick start
 
 - Open `index.html` in your browser.
 - Edit `styles.css` to customize colors, spacing, and layout.
 
 ## Features
 
 - Mobile-first layout with semantic HTML
 - CSS-only hamburger navigation (no JavaScript required)
 - Fluid typography with `clamp()`
 - Responsive grid for cards and content splits
 - Light/dark theme aware via `prefers-color-scheme`
 
 ## Customize
 
 - Colors and layout are driven by CSS variables at the top of `styles.css`.
 - Update the brand name and navigation links in `index.html`'s header.
 - Replace the About section's media block with your own image or illustration.
 
 ## Structure
 
 - `index.html` — Semantic document structure with sections
 - `styles.css` — Global styles, components, and utilities
 - `README.md` — This file
 
 ## Deploy
 
 Any static host works. For example, with `python`:
 
 ```bash
 python -m http.server 8080
 ```
 
 Then open `http://localhost:8080`.
 

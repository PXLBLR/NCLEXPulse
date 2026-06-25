# NCLEX Pulse — Marketing Site

The static landing page for **NCLEX Pulse**, an NCLEX-RN / NGN study app for iOS.

Plain HTML/CSS/JS — no build step. Served via **GitHub Pages**.

## Live
https://pxlblr.github.io/NCLEXPulse/

## Structure
- `index.html` — home / landing page
- `style.css` — design system (brand-matched to the iOS app)
- `main.js` — scroll-reveal + count-up interactions
- `privacy.html`, `terms.html`, `eula.html` — legal pages
- `assets/` — logo, App Store badge, app screenshots

## Develop
Just open `index.html` in a browser. To preview a production-like server:

```bash
python3 -m http.server -d . 8080
# http://localhost:8080
```

Educational use only — not clinical decision support. NCLEX® is a registered
trademark of the National Council of State Boards of Nursing, Inc. (NCSBN),
which does not endorse this product.

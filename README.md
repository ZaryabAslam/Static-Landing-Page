# Kaira — Bootstrap-only Homepage

This is a **pure HTML + CSS + Bootstrap** starter that recreates the top sections of the Kaira theme:
- Navigation bar
- Hero carousel with text/actions
- Feature list (icons + text)
- 3-up product grid (Shop for Men, Women, Accessories)

## How to use (as requested: Bootstrap via npm)

1. Open a terminal in this folder and install packages:
   ```bash
   npm install
   ```

2. Start a tiny static server (no frameworks, just to serve local `node_modules`):
   ```bash
   npm run dev
   ```
   Then open the printed local URL in your browser.

   > You can also open `index.html` directly in the browser. But serving via a local server is recommended so the `node_modules` paths work consistently.

3. Replace images in `assets/img/` with your own (keep the filenames or update the `<img>` `src` paths in `index.html`).

## Notes

- No custom JavaScript was written. The only runtime JS is Bootstrap's own bundle for the carousel.
- Icons come from **bootstrap-icons** (also installed via npm).
- Small CSS-only animations are included for hover/lift and caption fade-in.
- When you're ready, tell me what to add next and I'll extend the same project.

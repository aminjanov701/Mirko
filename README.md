# MIRKO IZOBASALT — HTML / CSS / JavaScript

This is a static vanilla version of the original MIRKO IZOBASALT site.

- HTML pages replace the Next.js/React pages.
- `styles.css` is the original global stylesheet, with only the Tailwind import removed so it works as plain CSS.
- `site.js` replaces the React/TypeScript client logic: language persistence, translation, calculator, forms, hero scroll interaction and optional 3D model loading.
- Original public assets are preserved.
- No TypeScript, React, Next.js or TSX source files are required to run the static site.

Run it with any static server, for example:
`python -m http.server 8080`

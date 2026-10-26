# Hortus Botanicus 2050 redesign

This static site is a fictional 2050 concept for the TU Delft Hortus Botanicus as the "Green Heart of Technology." It uses plain HTML, CSS and JavaScript only and is designed to run directly on GitHub Pages with no build step.

## Files
- `index.html` – the single-page landing experience with exactly five content sections and a footer.
- `style.css` – all visual design, responsive layout, and motion styles.
- `script.js` – minimal interactive behavior for sticky nav, mobile menu, reveal animations, and image binding.
- `images.js` – single source of truth for image paths and alt text.
- `images/pexels-reson-life-43382172-13601096.jpg` – the current portrait hero photo used across all slots.

## Swap the image later
1. Put your replacement image in the `images/` folder.
2. Update the matching entry in `images.js` by changing `src` and `alt`.
3. Keep the same key names and use them in HTML with `data-img="your-key"`.
4. Because the repo currently uses one portrait image, the design relies on CSS crop and positioning to keep it looking intentional across the page.

## GitHub Pages deployment
1. Commit these files to the repository's default branch or a Pages-enabled branch.
2. In GitHub, open the repository settings and enable GitHub Pages.
3. Choose the root folder for the static site if you are publishing from the default branch.
4. Save the site and open the generated GitHub Pages URL.

This is a fictional design concept and not the official TU Delft site.

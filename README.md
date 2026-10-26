# Hortus Botanicus 2050 redesign

This static site is a single-page concept for the TU Delft Hortus Botanicus in 2050.

## Files
- index.html: the full single-page site
- style.css: all styling
- script.js: menu, filters, language toggle, contrast toggle, agenda, scenario tool, reservation logic
- images.js: image paths and alt text

## How to add photos
1. Put your own image files in `assets/images/`.
2. Add a matching key in `images.js`.
3. Use the key in the HTML with `data-img="your-key"`.
4. Keep the file name and aspect ratio consistent with the intended layout.

## Image keys and subject suggestions
- hero: main hero image, 3:2
- intro: heritage and future image, 3:2
- abe: Architecture and the Built Environment, 4:3
- ceg: Civil Engineering and Geosciences, 4:3
- eemcs: EEMCS sensors and AI, 4:3
- ide: bio-inclusive façade, 4:3
- ae: Earth observation and habitat mapping, 4:3
- as: synthetic biology and plant metabolism, 4:3
- me: robotics and biomimicry, 4:3
- tpm: ethics and policy, 4:3
- partner_band: partner network and collaboration, 16:9
- support: supporters and donations, 4:3
- visit: visitor entrance and wayfinding, 3:2

## GitHub Pages deployment
1. Push these files to the GitHub Pages branch or default branch.
2. In the repository settings, enable GitHub Pages.
3. Use the default root folder for a static site.
4. Open the published URL to view the page.

This is a fictional 2050 design concept, not the official TU Delft site.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>README | Hortus Botanicus 2050</title>
    <meta name="description" content="Documentation for the Hortus Botanicus 2050 design concept website.">
    <link rel="stylesheet" href="css/styles.css" />
  </head>
  <body>
    <div class="container readme-wrap">
      <h1>Hortus Botanicus 2050 — future redesign</h1>
      <p>This is a static multi-page concept website inspired by the TU Delft Hortus Botanicus as it might exist in 2050, designed as a fictional but realistic institutional website.</p>

      <h2>Open the site</h2>
      <ol>
        <li>Open <code>index.html</code> directly in a browser, or</li>
        <li>Host the folder on GitHub Pages or any static host.</li>
      </ol>

      <h2>Deploy on GitHub Pages</h2>
      <ol>
        <li>Push this repository to GitHub.</li>
        <li>Open the repository settings.</li>
        <li>Go to Pages and choose the main branch / root folder.</li>
        <li>Save. The site will be served at your GitHub Pages URL.</li>
      </ol>

      <h2>Add your photos</h2>
      <p>All image paths live in one config file: <code>js/images.js</code>. Follow this workflow:</p>
      <ol>
        <li>Place your photo in the matching subfolder under <code>assets/images/</code>.</li>
        <li>Rename the file to match the key you want to use.</li>
        <li>Update the path in <code>IMAGES</code> in <code>js/images.js</code>.</li>
      </ol>

      <h2>Image key table</h2>
      <table>
        <thead>
          <tr>
            <th>Image key</th>
            <th>What it should show</th>
            <th>Recommended size / ratio</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>hero.main</td><td>Wide greenhouse scene with futuristic AR overlay</td><td>1600×900, 16:9</td></tr>
          <tr><td>garden.main</td><td>View across the living garden zones</td><td>1600×900, 16:9</td></tr>
          <tr><td>research.main</td><td>Researchers studying a plant or sensor array</td><td>1600×900, 16:9</td></tr>
          <tr><td>exhibitions.main</td><td>Faculty exhibition hall with people exploring</td><td>1600×900, 16:9</td></tr>
          <tr><td>experience.main</td><td>Immersive installation or future scenario display</td><td>1600×900, 16:9</td></tr>
          <tr><td>events.main</td><td>Event scene with visitors in the Hortus</td><td>1600×900, 16:9</td></tr>
          <tr><td>partners.main</td><td>Collaboration network or group meeting</td><td>1600×900, 16:9</td></tr>
          <tr><td>visit.main</td><td>Entrance, signage, or visitor path</td><td>1600×900, 16:9</td></tr>
          <tr><td>support.main</td><td>Community volunteers or donation moment</td><td>1600×900, 16:9</td></tr>
          <tr><td>education.main</td><td>Students or children learning in the garden</td><td>1600×900, 16:9</td></tr>
        </tbody>
      </table>

      <h2>Edit content</h2>
      <p>Editable content lives in the <code>data/</code> folder as JavaScript data files, designed to work without a build step and without <code>fetch</code> from a local file:</p>
      <ul>
        <li><code>data/site.js</code> — site text, opening hours, stats, and hero data</li>
        <li><code>data/events.js</code> — all agenda events</li>
        <li><code>data/exhibitions.js</code> — faculty exhibitions and filters</li>
        <li><code>data/partners.js</code> — partner content and categories</li>
      </ul>

      <h2>Assumptions</h2>
      <ul>
        <li>This is a fictional future-concept website, not the official TU Delft site.</li>
        <li>Some content is intentionally aspirational and editable.</li>
        <li>Photo files are placeholders by default until you add your own images.</li>
      </ul>
    </div>
  </body>
</html>

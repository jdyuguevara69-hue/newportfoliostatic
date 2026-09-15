# Static PHP Portfolio

This is the Laravel portfolio converted into a standalone PHP page.

## Files
- `index.php` — the complete portfolio (HTML + CSS, with only a PHP year).
- `images/profile.jpg` — profile photo.
- `cv/GUEVARA_CV.pdf` — CV.
- `favicon.ico` — favicon.

No Laravel, Composer, database, Node.js, Vite, or external build process is required.

## Important: GitHub Pages
GitHub Pages does **not execute PHP**. If you deploy this repository specifically with GitHub Pages, `index.php` will not run as PHP.

For GitHub Pages, use an `index.html` version of this same file (replace `<?= date('Y') ?>` with the current year). For a PHP host, upload this folder as-is.

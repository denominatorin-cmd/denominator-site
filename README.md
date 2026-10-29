# Denominator Digital site
Static site, no build step. All links are relative (works on GitHub Pages under a subpath).

## Add a new industry
1. Copy `industries/clinics.html` to `industries/<name>.html` (e.g. `salons.html`). It uses `../style.css`.
2. Edit the title, meta description, hero, "What X get" cards and the demo section (remove the demo section if there is no demo yet).
3. Add the page to the **Industries dropdown** in the `<nav>` of every page (`index.html` and each file in `industries/`): `<a href="industries/<name>.html">` on the homepage, `<a href="../industries/<name>.html">` in industry pages.
4. Add a card in the `#industries` section of `index.html` (copy the Clinics `<a class="card ind">` block).

## Before deploying
Replace `DEMO_URL` in `industries/clinics.html` with the live SmileCraft demo URL.

# Schazeril Consulting website

A static multi-page site. No build step is needed: GitHub Pages serves the files as they are.

## Pages
| File | Page |
|---|---|
| `index.html` | Home |
| `exosystem.html` | What We Do (the four pillars) |
| `executive-advisor.html` | SC Executive Advisor |
| `about.html` | Who We Are |
| `contact.html` | Contact |
| `404.html` | Not found page |

All pages share `assets/css/style.css`. Images are in `assets/img/`.

## Deploy to GitHub Pages
1. Create a new repository, for example `schazeril-website`.
2. Upload everything in this folder to the root of the repository, including the empty `.nojekyll` file.
3. In the repository, go to **Settings > Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, then select the `main` branch and the `/ (root)` folder. Save.
5. After a minute or two the site is live at `https://<username>.github.io/schazeril-website/`.

## Custom domain (optional)
1. In **Settings > Pages > Custom domain**, enter the domain, for example `www.schazeril.com`.
2. At the domain registrar, add a CNAME record pointing `www` to `<username>.github.io`.
3. Tick **Enforce HTTPS** once the certificate is issued.

## Before going live
- **Contact form:** GitHub Pages cannot process forms. Create a free endpoint at Formspree (or similar) and replace `YOUR_FORM_ID` in `contact.html`.
- **Portrait:** replace `assets/img/schazeril.jpg` with the original high-resolution photo (square, at least 1200 x 1200 px).
- **Logo:** replace `assets/img/logo-white.png` and `assets/img/logo.png` with the original vector or high-resolution files.
- **Content:** confirm the pillar descriptions and "Signs you need this" lists on `exosystem.html` with Schazeril.

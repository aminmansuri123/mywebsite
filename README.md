# Personal site — Amin Mansuri

Static HTML/CSS/JS site for GitHub Pages: finance, systems, MIS, and automation positioning.

## Before you publish

1. **Email & LinkedIn** — In `index.html`, replace `your.email@example.com` and `https://www.linkedin.com/in/your-profile`.
2. **Resume PDF** — Add your file as `assets/Amin-Mansuri-Resume.pdf` (same path as the download button).
3. **Contact form** — Create a free form at [formspree.io](https://formspree.io), copy your form endpoint, and in `index.html` replace `https://formspree.io/f/YOUR_FORM_ID` in the `<form action="...">` attribute.

## Host on GitHub Pages

1. Create a new repository on GitHub (for example `aminmansuri` or `mywebsite`).
2. Push this folder to the repo (main branch):

   ```bash
   cd d:\App\MyWebsite
   git init
   git add .
   git commit -m "Initial personal site"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose branch **main** and folder **/ (root)**, then save.

After a minute, the site is available at:

`https://YOUR_USERNAME.github.io/YOUR_REPO/`

If the repository name is `YOUR_USERNAME.github.io`, the site URL is `https://YOUR_USERNAME.github.io/`.

## Local preview

Open `index.html` in a browser, or run a quick static server:

```bash
npx --yes serve .
```

Then visit the URL shown in the terminal (often `http://localhost:3000`).

## Structure

| Path | Purpose |
|------|---------|
| `index.html` | All sections (home, about, projects, skills, insights, resume, contact) |
| `css/styles.css` | Layout, theme (white / dark blue / grey), responsive rules |
| `js/main.js` | Mobile nav, scroll reveals, contact form helper |
| `assets/` | Resume PDF (you add) |

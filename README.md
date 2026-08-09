# AMFiTech Solutions — Amin Mansuri

Static HTML/CSS/JS site for GitHub Pages.

## Contact form (Web3Forms)

Inquiries go to **info@amfitech.in** via [Web3Forms](https://web3forms.com).

1. In Web3Forms → **Settings**, confirm the destination email is `info@amfitech.in`.
2. Send a test message from the live Contact form.
3. Check **info@amfitech.in** (and spam) plus Web3Forms → **Submissions**.

## Host on GitHub Pages

1. Push this folder to GitHub (`main` branch).
2. **Settings → Pages** → deploy from **main** / **root**.
3. Custom domain: `aminmansuri.xyz` (see GitHub Pages custom domain + Namecheap A/CNAME records).

## Local preview

```bash
npx --yes serve .
```

## Structure

| Path | Purpose |
|------|---------|
| `index.html` | Home, About, Contact |
| `css/styles.css` | Layout and theme |
| `js/main.js` | Mobile nav, scroll reveals, contact form |

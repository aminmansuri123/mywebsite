# AMFiTech Solutions — Amin Mansuri

Static HTML/CSS/JS site for GitHub Pages.

## Contact form (free, delivers to email)

Inquiries go to **info@amfitech.in** via [FormSubmit](https://formsubmit.co) — no account required.

1. Submit the form once from the live site.
2. Open **info@amfitech.in** and click the FormSubmit confirmation link (one-time).
3. After that, messages arrive in that inbox.

If you prefer another free option later: [Web3Forms](https://web3forms.com) (API key) or [Formspree](https://formspree.io).

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

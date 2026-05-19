# Automa8 Landing Page

A clean, modern landing page for Automa8 — automation and AI workflow solutions.

## Setup

1. Fork or clone this repository
2. Go to **Settings → Pages** in your GitHub repo
3. Set source to **Deploy from a branch** → `main` → `/ (root)`
4. Your site will be live at `https://yourusername.github.io/repo-name/`

## Customize

### Change the Booking URL
Open `index.html` and find this comment near line 230:
```html
<!-- ✏️ CHANGE YOUR BOOKING URL HERE -->
<a href="#" class="cta-button" ...>
```
Replace `#` with your booking URL (e.g., `https://calendly.com/your-link`).

### Files
- `index.html` — The landing page
- `automa8_white_logo.png` — Logo asset
- `favicon.svg` — Browser tab icon
- `Automa8-Landing-Page.pdf` — Desktop PDF flyer (landscape)
- `Automa8-Mobile-Landing-Page.pdf` — Mobile PDF flyer (portrait)

## Custom Domain
To use a custom domain (e.g., `automa8.com`):
1. Go to **Settings → Pages → Custom domain**
2. Enter your domain
3. Add a CNAME record pointing to `yourusername.github.io`

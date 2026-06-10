# Aura Wigs — Custom Wig PWA

A mobile-first Progressive Web App for a custom wig business. Built as a zero-backend, single-file MVP deployable on GitHub Pages.

## Features

- **Home** — Hero, featured wigs, how it works
- **Catalog** — 12 wig listings, search, filter by type
- **Virtual Try-On** — Upload photo + canvas overlay (no AR SDK, no fees)
- **Order** — WhatsApp + email CTAs, order form

## Tech Stack

- Pure HTML/CSS/JS — no frameworks, no dependencies
- Canvas API for try-on overlay
- PWA manifest — installable from mobile browser
- Zero backend — all order flow goes to WhatsApp/email

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app is live at `https://yourusername.github.io/aurawigs`

## Customization

Before going live, update the following in `index.html`:

- WhatsApp number: search `wa.me/17185550000` and replace with real number
- Email: search `orders@aurawigs.com` and replace
- Wig names, prices, descriptions: update the `WIGS` array in the script
- Wig emoji: swap emojis with real product photos by replacing `<div class="wig-emoji">` with `<img>` tags

## Portfolio Note

Built by [Solo730 Multimedia LLC](https://github.com/solo730) as a reusable template for beauty/hair e-commerce clients.

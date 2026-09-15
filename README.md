# Margulan Baizhakyp Portfolio

A minimal single-page portfolio for `mbaizhakyp.com`.

## Edit Points

- Featured projects live in the `project-list` in `index.html`; secondary ones in `more-list`.
- Experience and skills are in the `#experience` section; contact links in `#contact`.
- Replace or update the resume PDF at `assets/Margulan_Baizhakyp_Resume.pdf`.
- Colors and type are CSS custom properties at the top of `styles.css`; dark mode follows the system setting.
- Bump the `?v=` query on the stylesheet link in `index.html` when you change `styles.css` so browsers pick it up.

## Preview Locally

Open `index.html` directly in a browser, or run:

```sh
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## Deployment

This site is plain HTML, CSS, and JavaScript, so it can be deployed to Vercel,
Netlify, Cloudflare Pages, GitHub Pages, or any static hosting provider.

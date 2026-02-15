# jackladbrook.com

Personal website for Jack C Ladbrook — Cyber Security Architect.

## Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended edition, v0.110+)

## Local Development

```bash
hugo server -D
```

Open http://localhost:1313 in your browser.

## Build

```bash
hugo
```

Output is generated in the `public/` directory.

## Deploy

Upload the contents of `public/` to any static hosting provider (Netlify, Cloudflare Pages, GitHub Pages, etc.).

### Cloudflare Pages / Netlify

- Build command: `hugo`
- Output directory: `public`
- Hugo version env var: `HUGO_VERSION = 0.142.0`

## Customisation

- **Photo:** Add your headshot to `static/images/headshot.jpg` and update the placeholder in `themes/jcl/layouts/index.html`
- **Email:** Update the email address in the Contact section of `themes/jcl/layouts/index.html`
- **Colours:** Edit CSS variables in `themes/jcl/static/css/style.css`

# Sidequest Website

Static marketing and support website for the Sidequest iPhone app.

## App Store URLs

- Marketing URL: publish `index.html` and use the root URL, for example `https://sidequest.pages.dev/`
- Support URL: publish `support.html` and use `https://sidequest.pages.dev/support.html`

## Before Publishing

Current support email in `support.html`:

```html
mailto:pcesnek290@gmail.com?subject=Sidequest%20Support
```

## Free Hosting

This site has no build step. Upload the whole `sidequest-website` folder or the generated zip file to a static host.

Good options:

- Cloudflare Pages: direct upload or Git deploy, gives a `*.pages.dev` URL.
- Netlify: drag-and-drop deploy or Git deploy, gives a `*.netlify.app` URL.
- GitHub Pages: Git-based deploy, gives a `*.github.io` URL.
- Vercel: Git or CLI deploy on the free Hobby plan for personal projects.

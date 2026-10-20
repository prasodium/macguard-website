# MacGuard website

The one-page site and docs for [MacGuard](https://github.com/prasodium/MacGuard).

- `index.html` is the landing page, `docs.html` the documentation, `404.html` the not-found page.
- Plain HTML and CSS, no build step, no JavaScript and no external requests. Light and dark themes follow the system.

## Preview locally
```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Hosting
Served by GitHub Pages from the `main` branch root: **https://prasodium.github.io/macguard-website/**
(Settings → Pages → Build and deployment → Deploy from a branch → `main` / root.) All links are relative, so it also works from a custom domain or any static host.

## Keep it honest
The status table on the home page and the "Testing status" section of the docs mirror the real state of the app (see its `TESTING.md`). Update them when something gets verified on hardware.

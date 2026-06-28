# mitty.film

The one-page marketing site for **mitty** — _your life is the movie._

Mitty turns your camera roll into cinematic posts, already in your voice.

## What's here

- `index.html` — the entire single-page site (self-contained: inline CSS + a little JS, no build step).
- `CNAME` — custom domain (`mitty.film`) for GitHub Pages.

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy (GitHub Pages)

This branch is set up to publish via GitHub Pages from the repo root. Once Pages
is enabled (Settings → Pages → Deploy from branch), the `CNAME` file points the
build at `mitty.film`. See the PR description for the GoDaddy DNS steps.

Design language matches the mitty app preview: Fraunces + Inter, a warm
cream/ink/gold palette, and the cinematic, lowercase editorial voice.

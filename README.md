# High Expectations FF — Fantasy League Weekly

The weekly fantasy football newspaper for the **High Expectations** Sleeper league.

A static site — no build step, no backend. Served as-is.

## Files

- `index.html` — page markup and content (weekly editions, previews, reviews, history)
- `styles.css` — all styling
- `app.js` — tab switching, week dropdown, and other page behavior

## Deploying

Hosted with [Cloudflare Pages](https://pages.cloudflare.com/): connect this repo,
set the build output to the repo root (no build command), and every push to `main`
redeploys the site.

## Updating content

Weekly editions are refreshed from league data (Sleeper API + NFL news) and
committed here; Cloudflare Pages picks up the changes automatically.

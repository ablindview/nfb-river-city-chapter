# NFB River City Chapter website

Website for the River City Chapter (Sacramento) of the National Federation of the Blind of California.

A single static page (`index.html`) with no build step. It is written for screen readers first and follows WCAG 2.2 AA: semantic landmarks, a skip link, one heading per level, visible focus, 24px+ targets, and a light/dark theme that follows the device with a manual override.

## Local preview

Open `index.html` in any browser, or run `npx serve .`.

## Deploy

Hosted on Cloudflare Pages. Every push to `main` deploys automatically once the repository is connected in the Cloudflare dashboard, or deploy by hand with:

```
npx wrangler pages deploy . --project-name nfb-river-city-chapter
```

# Infinity Life — Public Support Pages

Static, unauthenticated support pages for the **Infinity Life** mobile app
(Android package `com.infinitycar.app`, published on Google Play).

Served via **GitHub Pages** — no build step, pure HTML.

## Pages

| Path | Purpose |
|------|---------|
| `index.html` | Landing page listing available support resources |
| `delete-account.html` | Google-Play-compliant account & data deletion instructions |

## Public URLs

Once GitHub Pages is enabled on this repo (Settings → Pages → branch `main`,
folder `/ (root)`):

- Root:    `https://<owner>.github.io/infinity-life-support/`
- Delete:  `https://<owner>.github.io/infinity-life-support/delete-account.html`

The **delete-account** URL is what you paste into Google Play Console →
**App content → Data safety → Data deletion → URL**.

## What this repo intentionally does NOT contain

- No application source code
- No API keys, tokens, secrets, or environment files
- No user data of any kind
- No build/CI configuration

Everything here is static HTML + CSS, safe to be public.

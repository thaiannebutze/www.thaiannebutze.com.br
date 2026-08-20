# AGENTS.md — www.thaiannebutze.com.br site repo

This is the **public site repository** for www.thaiannebutze.com.br. Repo root is the site.

## Generated (do not hand-edit)

- `index.html`, `404.html`, `styles.css`
- `robots.txt`, `sitemap.xml`
- `privacy.html`, `terms.html`
- `og-image.png`, `favicon.svg`

Regenerate from company repo with `/startup.site`.

## Authored in company repo

- Content comes from `thaiannebutze.com.br/story/` and `thaiannebutze.com.br/profile.yaml`
- Design from `thaiannebutze.com.br/brand/design.md` and `tokens.json`

## Never put here

- Private contact data (only `public: true` contacts reach the site)
- Secrets, API keys, analytics credentials

## Deploy

Push to `main` triggers GitHub Pages deploy via `.github/workflows/deploy-pages.yml`.

## Constraints

GitHub Pages cannot set custom HTTP headers (no CSP, no HSTS).

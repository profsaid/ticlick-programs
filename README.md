# Ticlick Programs — prototype

Interactive HTML prototype of the Ticlick CRM programs flows (Exchange & Study Abroad).

- Live: https://ticlick-programs0.saeed.design
- Page: `public/index.html` (single self-contained file)
- Hosting: Cloudflare Workers static assets (`wrangler.jsonc`)

## Deploy

```bash
npx wrangler deploy
```

Or connect this repo in Cloudflare (Workers → ticlick-programs0 → Settings → Builds) so every push to `main` deploys automatically.

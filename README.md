# footgifts.com

Foot Gifts — Curated Foot Appreciation.

A separate community/membership site (AI models, exclusive galleries, membership
tiers) — **not** a redirect to footgift.com. The two domains serve distinct
sites:

| Domain | Site | Repo |
|--------|------|------|
| footgift.com | Curated Foot Care & Beauty (products, blog) | gregs535/footgift-com |
| footgifts.com | Curated Foot Appreciation (community/membership) | gregs535/footgifts-com |

Deployed via GitHub Pages with custom domain `footgifts.com` (CNAME in repo root).

## Deploy

```bash
# From this repo root (domains/footgifts-com/):
git add -A && git commit -m "update" && git push origin main
```

GitHub Pages serves `index.html` from the `main` branch root. The main site
links back to [footgift.com](https://footgift.com) for products.

# Home Specialists HQ

Roofing cost-guide landing page for homespecialistshq.com.

- `public/index.html` is the quiz page. Settings (offer link, state blocks) are in the CONFIG block at the top of its script.
- `public/privacy.html` and `public/terms.html` are the legal pages.
- `wrangler.jsonc` tells Cloudflare to serve `public/` as a static site. Every push to `main` deploys.

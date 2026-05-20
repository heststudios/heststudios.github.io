# heststudios.github.io

Official website for **Hest Studios** — independent mobile game studio.

## Structure

```
/
├── index.html                       # Landing page
├── privacy.html                     # General privacy policy
├── support.html                     # Support & FAQ
├── app-ads.txt                      # AdMob authorized sellers
├── 404.html                         # Error page
└── route-tycoon/
    └── privacy.html                 # Route Tycoon game-specific privacy
```

## Live URLs

Once GitHub Pages is enabled, these will be live:

- `https://heststudios.github.io/`
- `https://heststudios.github.io/privacy.html`
- `https://heststudios.github.io/support.html`
- `https://heststudios.github.io/app-ads.txt`
- `https://heststudios.github.io/route-tycoon/privacy.html`

When `heststudios.com` is registered and pointed at GitHub Pages, all URLs
above will also work at `https://heststudios.com/...`.

## Deployment

This is a static site served by GitHub Pages from the `main` branch root.

To set up:
1. Create a new GitHub repo named `heststudios.github.io` under the `heststudios` org/user
2. Push these files to the `main` branch
3. Go to Settings → Pages → Source: `Deploy from a branch` → `main` / `/ (root)`
4. Wait ~1 minute, site goes live at `https://heststudios.github.io`

## Custom Domain (future)

When ready to switch to `heststudios.com`:
1. Buy domain at any registrar (Namecheap, Cloudflare, etc.)
2. In repo Settings → Pages → Custom domain: enter `heststudios.com`
3. At your DNS provider, add these records:
   - `A` record: `@` → `185.199.108.153`
   - `A` record: `@` → `185.199.109.153`
   - `A` record: `@` → `185.199.110.153`
   - `A` record: `@` → `185.199.111.153`
   - `CNAME` record: `www` → `heststudios.github.io`
4. Add a file called `CNAME` in repo root with one line: `heststudios.com`
5. Enable "Enforce HTTPS" in Settings → Pages

## License

© 2026 Hest Studios. All rights reserved.

# phoebebotsford.com

Static site for Phoebe Botsford, LPCC — served by GitHub Pages.

## Files
- `index.html` — the whole site (inline CSS)
- `assets/headshot.jpg` — **add this** (portrait, ~4:5). Until it exists, a "PB" monogram shows.
- `CNAME` — custom domain for GitHub Pages
- `favicon.svg`, `.nojekyll`

## Deploy
1. Create a public repo (e.g. `phoebebotsford.com`) and push these files to `main`.
2. Repo → Settings → Pages → Source: *Deploy from a branch*, `main` / `/ (root)`.
3. DNS at your registrar for `phoebebotsford.com`:
   - `A` @ → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `AAAA` @ → 2606:50c0:8000::153, 2606:50c0:8001::153, 2606:50c0:8002::153, 2606:50c0:8003::153
   - `CNAME` www → `<github-username>.github.io`
4. Back in Settings → Pages, confirm the custom domain, wait for the cert, then tick **Enforce HTTPS**.

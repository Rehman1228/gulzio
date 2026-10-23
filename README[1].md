# Gulzio website

Static site (no build step). Files: `index.html` and `assets/`.

## Publish free on GitHub Pages
1. Create a new GitHub repo, e.g. `gulzio` (public).
2. Upload everything in this folder (keep the `assets` folder and `.nojekyll`).
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/gulzio/`.

## Use gulzio.com
Settings → Pages → Custom domain → `gulzio.com`. At your domain registrar add:
- A records for `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- CNAME for `www` → `YOUR-USERNAME.github.io`
Then tick "Enforce HTTPS".

## Before you publish
- Update the LinkedIn link in the Contact section to your company page URL.
- Replace the email if you want a business address.

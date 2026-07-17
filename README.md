# Legal pages for App Store Connect

English **Privacy Policy** and **Support** pages for GitHub Pages (or any static host).

## Files

| File | Use |
|------|-----|
| `privacy.html` | **Privacy Policy URL** in App Store Connect |
| `support.html` | **Support URL** in App Store Connect |
| `index.html` | Optional hub |
| `privacy.md` / `support.md` | Editable Markdown sources (keep in sync with HTML when you change copy) |
| `styles.css` | Shared styles |

## Publish with GitHub Pages (recommended)

### Option A — Separate public repo (cleanest)

1. Create a **public** repo, e.g. `parkpin-legal`.
2. Copy everything in this `legal/` folder to the repo root (or `/docs`).
3. GitHub → **Settings → Pages**:
   - Source: Deploy from a branch
   - Branch: `main` / root (or `/docs` if you put files there)
4. After a minute, open:
   - `https://YOUR_USER.github.io/parkpin-legal/privacy.html`
   - `https://YOUR_USER.github.io/parkpin-legal/support.html`
5. Paste those URLs into App Store Connect.

### Option B — This repo

1. Make the repo **public** (or use a public `gh-pages` branch).
2. Settings → Pages → branch `main` → folder `/docs`.
3. URLs will look like:
   - `https://YOUR_USER.github.io/REPO_NAME/legal/privacy.html`
   - `https://YOUR_USER.github.io/REPO_NAME/legal/support.html`

## App Store Connect fields

- Privacy Policy URL → `.../privacy.html`
- Support URL → `.../support.html`

Contact email used in pages: `surival987@gmail.com`

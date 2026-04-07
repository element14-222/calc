# Barreletics wholesale calculator (public GitHub Pages)

**Source of truth for edits:** `barreletics-project/docs/index.html` — copy that file here when you change the calculator, then commit this repo.

## Why this repo is public

GitHub **Free** only publishes **public** `github.io` sites. The in-page username/password is **not** GitHub security—it only hides the UI from casual visitors; anyone can still read the HTML/JS (and your tiers/password strings) in “View source.” Do not treat this as protection for truly secret data.

## New repo + URL (once)

1. On GitHub: **New repository** → name e.g. `barreletics-wholesale-calculator` → **Public** → create **without** README.
2. On your Mac, in **this folder** (`wholesale-calculator-public-site`):

```bash
git init
git add index.html README.md
git commit -m "Initial wholesale calculator"
git branch -M main
git remote add origin https://github.com/YOUR_USER_OR_ORG/barreletics-wholesale-calculator.git
git push -u origin main
```

3. GitHub → repo **Settings** → **Pages** → **Deploy from a branch** → **main**, folder **/ (root)** → **Save**.
4. After ~1–2 minutes, open: `https://YOUR_USER_OR_ORG.github.io/barreletics-wholesale-calculator/`

**Login:** username `barreletics`, password `barreletics8` (change both in `index.html` if needed).

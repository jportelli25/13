# jportelli25.github.io/13 — website (public)

The **public** website + legal/support pages for the "13 / Tiến Lên" app (iOS + Android).
This repo holds **only** the website — the app source code lives in a separate **private** repo.

Live URLs (GitHub Pages serves this repo's **root**):

| Page | URL |
|---|---|
| Landing | https://jportelli25.github.io/13/ |
| Privacy policy | https://jportelli25.github.io/13/privacy-policy.html |
| Support / FAQ | https://jportelli25.github.io/13/support.html |

## Enable GitHub Pages (one time)
Repo **Settings → Pages** → Source = **Deploy from a branch** → Branch = **`main`**, Folder = **`/ (root)`** → Save.
(The `/13/` in the URL is just this repo's name.)

## Update the pages
Edit the `.html` files here, then:
```sh
git add -A && git commit -m "update site" && git push
```
Changes go live in ~1 minute. Internal links between pages are relative, so they keep working.

# go-retrovision.github.io

Artwork-only splash for https://go-retrovision.github.io/

Flat folder (no subdirectories):

- `index.html`
- `styles.css`
- `retrovision-splash.png`
- `retrovision-favicon.png`
- `retro-vault-mark.png`
- `panda-mark.png`
- `README.md`

## Publish

1. Create a **public** repo named `go-retrovision.github.io` under `go-retrovision` if needed.
2. From this folder:

```powershell
cd C:\Users\julia\go-retrovision.github.io
git init
git add .
git commit -m "Initial RetroVision Pages splash"
git branch -M main
git remote add origin https://github.com/go-retrovision/go-retrovision.github.io.git
git push -u origin main
```

3. Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)`.

## Local preview

Open `index.html` in a browser.

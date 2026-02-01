# Valentine Proposal App

A playful, single-file web app to ask: "Will you be my Valentine?" with heart confetti, a cheeky "No" button, and a shareable link.

## How to Run

- Double-click `index.html` to open it in your browser, or in PowerShell from the workspace root:

```powershell
Start-Process ".\Valentine Proposal\index.html"
```

## Features

- Personalize with recipient and message
- Playful Yes/No interactions
- Confetti hearts celebration
- Shareable link with prefilled text via URL parameters
- Mobile-friendly and lightweight (no external libraries)

## Customize

Open `index.html` and tweak the styles (colors, sizes) or text to fit your vibe. Add images or a photo by placing files in the same folder and referencing them in the HTML.

## Deploy

Make your share link accessible to anyone by hosting the folder. Three easy options:

### GitHub Pages (simple)
- Create a new repo and add the `Valentine Proposal/` contents to the repo root.
- Commit and push to `main`.
- In GitHub → Settings → Pages: Source = `Deploy from a branch`, Branch = `main` and `/ (root)`.
- Your site will be available at `https://<username>.github.io/<repo>/`.

### Netlify (drag & drop)
- Go to netlify.com → Sites → Drag & drop the `Valentine Proposal/` folder.
- Optional: keep `netlify.toml` for defaults.

### Vercel (import)
- Create a new project in Vercel, import your repo containing this folder.
- Vercel auto-detects static sites; `vercel.json` is included for clarity.

Once hosted, the “Copy share link” will produce a URL like `https://your-host/index.html?to=Alex&msg=Dinner%20Friday%3F&from=Jamie` that works anywhere.

# Buena Vista Landing Page

Live URL: https://buena-vista-landing.pages.dev
GitHub: https://github.com/bohdanshev/buena-vista-landing

Auto-deploys to Cloudflare Pages on every push to `main`.

---

## Repo structure

```
buena-vista-landing/
├── index.html        ← The landing page (edit this)
├── style.css         ← All styles (edit this)
└── images/           ← All food/author photos
    ├── hero.jpeg
    ├── lobster-ravioli.jpeg
    ├── paella.png
    ├── sea-bass.png
    ├── steak.png
    ├── duck.png
    ├── tamales.png
    ├── squid-ink.webp
    └── isabella.jpg
```

---

## How to push a new version

### First time (clone the repo)
```bash
git clone https://github.com/bohdanshev/buena-vista-landing.git
cd buena-vista-landing
```

### Every time you update the page

1. Make your changes to `index.html` or `style.css`

2. To replace an image — drop the new file into `images/` using the **exact same filename**

3. Push:
```bash
git add .
git commit -m "short description of what you changed"
git push
```

Cloudflare updates automatically within ~30 seconds. No extra steps needed.

---

## Image naming rules
- No spaces in filenames (use hyphens: `sea-bass.png` not `sea bass.png`)
- Keep the same filename when replacing an image so the HTML doesn't break
- Supported formats: `.jpg`, `.jpeg`, `.png`, `.webp`

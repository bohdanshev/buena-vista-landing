# Buena Vista Landing Page

Live URL: https://buena-vista-landing.pages.dev

## Structure

```
buena-vista-landing/
├── index.html        ← The landing page
├── style.css         ← All styles
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

## How to update the page

1. Clone the repo (first time only):
   ```
   git clone https://github.com/bohdanshev/buena-vista-landing.git
   cd buena-vista-landing
   ```

2. Make your changes to `index.html` or `style.css`

3. If replacing an image, drop the new file into `images/` using the same filename

4. Push to deploy:
   ```
   git add .
   git commit -m "describe what you changed"
   git push
   ```

That's it — Cloudflare auto-deploys within ~30 seconds of every push to `main`.

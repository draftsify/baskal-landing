# Baskal — Landing Page

Landing page for **Baskal**, a mobile app that tells you exactly what groceries
to buy based on your **budget, calorie goals, nutrition goals, and preferred
supermarket**.

**Set your goals. Get the exact groceries you need.**

🔗 **Live:** https://baskal.vercel.app

## Design
Dark, minimal "scanner" aesthetic (à la Cal AI): charcoal + white, cool X-ray
accent. The hero is a **BASKAL** shopping basket surrounded by grocery items
rendered as **pixelated X-ray scans** — the mystery Baskal decodes into a clear list.

- Static HTML/CSS, no build step, no dependencies.
- Fonts: Manrope (display) + Switzer (body), self-hosted.
- Basket + X-ray items generated with **Higgsfield** (Nano Banana Pro); X-ray items
  downscaled and rendered with `image-rendering:pixelated` + `mix-blend-mode:screen`.

## Structure
```
index.html
assets/img/basket.jpg      # rim-lit BASKAL basket
assets/xray/*.png          # pixelated x-ray mystery items
assets/fonts/*.woff2       # Manrope + Switzer
```

## Deploy
Static — deploy the folder as-is (e.g. `vercel --prod`).

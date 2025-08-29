[README.md](https://github.com/user-attachments/files/22048612/README.md)
# Crafty Worth — Gift Store (Static Preview)

A simple, fast **static preview** of the Crafty Worth storefront built with **HTML + Tailwind (CDN)** and a little vanilla JS (cart, login modal, notifications). Perfect for showing the design and basic flows without a backend.

> This repo is meant for **GitHub Pages live preview** and quick demos. No server required.

---

## 🚀 Live Preview

Once GitHub Pages is enabled, your site will be here:

**https://craftyworthcw-svg.github.io/gift-store/**

If you just enabled Pages and the link shows 404, wait ~1–2 minutes and refresh (or add a trailing `/`).

---

## 📦 What’s inside?

```
/ (root)
├─ index.html   # The whole demo site
└─ README.md    # This file
```

**Features included**

- Hero section with brand gradient
- Product grid (4 sample items)
- Add to Cart (client-only, no payments)
- Cart modal with remove/update and total
- Simple Login modal (simulated)
- Responsive layout with Tailwind CDN
- Lightweight notifications/toasts

> Note: This is a **static demo**—no database, no payments. Ideal for UI/UX review and client preview.

---

## 🌐 Publish on GitHub Pages (1 minute)

1. Go to **Settings → Pages** in this repo.  
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.  
3. Set **Branch:** `main` and **Folder:** `/ (root)`, then **Save**.  
4. After 30–90 seconds, Pages shows your live link at the top of the same screen.  
5. Open: **https://craftyworthcw-svg.github.io/gift-store/**

**Common gotchas**
- If the link 404s, refresh after a minute or add a trailing slash `/`.
- Make sure the repository is **Public**.
- Ensure `index.html` is in the **root** of the repo (not inside a folder).

---

## 🖥️ Run locally (no install)

Option A — **Double‑click `index.html`** to open in your browser.  
Option B — Use VS Code + **Live Server** extension for auto‑reload.

---

## ✏️ How to edit content

Open `index.html` and look for these sections:

- **Header / Nav** — update categories or add links.  
- **Hero** — change the headline & subheadline.  
- **Products grid** — change product titles, prices, badges.  
- **Login & Cart modals** — copy changes to text or buttons.  
- **Footer** — update phone, email, city.

> Tailwind styles work directly because we load it via CDN at the top of the file.

---

## 🛣️ Next steps (optional)

- Add more pages (make `about.html`, `contact.html`, etc.) and link them from the nav.  
- Move to a framework (Next.js) and connect real backend (auth, orders, payments).  
- Add analytics (GA4/GTM) and SEO metadata (title, description, OG tags).  
- Hook image uploads to AWS S3 via presigned URLs (when you’re ready for backend).

If you want, open an issue in this repo for a **Next.js full-stack upgrade prompt** and we’ll paste the exact scaffold instructions.

---

## 🧰 Tech Notes

- **Tailwind CSS** via CDN: no build step.  
- **Vanilla JS** only—no bundlers.  
- State is in-memory; refreshing the page resets the cart.  
- Works on mobile; use Chrome DevTools to test responsive sizes.

---

## 📝 License

MIT — do whatever you want, attribution appreciated.

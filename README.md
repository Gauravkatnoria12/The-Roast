# ☕ The Roast — Luxury Coffee Experience

Hey! 👋 Welcome to the source code for **The Roast** — a cinematic, premium landing page concept for a high-end artisanal coffee roastery. This one was all about vibes. Dark, slow, intentional, luxurious. ✨

---

## 🌑 What Is This?

A single-page marketing website for a fictional luxury coffee brand. Think less Starbucks, more "private members club that happens to serve coffee." The design language borrows from high-fashion editorial and luxury goods — tight tracking, gold accents, oversized serif type, and a lot of dark space doing a lot of heavy lifting. 🖤

Built entirely in one HTML file. No frameworks, no build tools, just Tailwind via CDN and a handful of vanilla JS lines.

---

## ✨ Features

- ⏳ **Animated Loader** — A gold progress bar slides across while *The Roast.* fades in — clean and unhurried
- 🎬 **Slow-Zoom Hero** — The background image perpetually and slowly zooms in over 30 seconds via a CSS `@keyframes` animation. It's subtle but it makes the hero feel alive
- 🌫️ **Blur + Fade Reveal System** — Scroll-triggered elements don't just fade in, they also un-blur (`filter: blur(20px)` → `blur(0)`) for a cinematic unveiling effect
- ⏱️ **Staggered Animations** — Three delay tiers (`.stagger-1`, `.stagger-2`, `.stagger-3`) make grouped elements cascade in naturally
- 🥇 **Collector's Series Cards** — Offset grid layout where the middle card drops lower than the others, creating visual depth without any JS
- 🔍 **Hover Image Zoom on Cards** — Product images scale up on hover with a 1-second eased transition
- 📜 **Custom Gold Scrollbar** — The browser scrollbar is styled with `var(--gold)` so even that feels premium
- 🧭 **Shrinking Navbar on Scroll** — Nav padding tightens and background deepens after 50px of scroll
- 📱 **Fully Responsive** — Every section reflows cleanly from mobile to 4K

---

## 🛠️ Tech Stack

| What | How |
|---|---|
| Markup | HTML5 |
| Styling | Tailwind CSS (CDN) + custom CSS |
| Fonts | Playfair Display (serif) · Inter (sans-serif) |
| Images | Unsplash (hero, cards, heritage) · Local (`process.png`, `detail.png`) |

No npm. No webpack. No React. Just a browser and a text editor. 🙌

---

## 🎨 Design Language

Every decision here was made in service of one feeling: **quiet luxury.**

- **Gold (`#c5a059`)** — The only warm accent in an otherwise cold, dark palette. Used sparingly so it always pops
- **Stone Dark (`#0a0908`)** — Not quite black, has a warmth to it. Feels like a dark espresso, not a void
- **Playfair Display italic** — The hero headline in italics at 140px feels like a magazine cover
- **Tight letter-spacing on all caps labels** (`tracking-[0.4em]`) — A classic luxury brand trick, used throughout navigation, tags, and footers
- **Blur-to-reveal scroll animations** — More disorienting and cinematic than a simple fade, like the image is being developed in front of you
- **Offset card grid** — The middle card sitting 6rem lower than its siblings creates a cascading rhythm without any JavaScript
- **Grayscale hero image with `grayscale-[0.2]`** — Not fully desaturated, which would feel cold, but close enough to feel editorial

---

## 📁 File Structure

```
the-roast/
│
├── assets          # images
├── index.html      # The whole site — one file
└── README.md       # You're here!
```

## 🚀 Running It

```bash
# Clone it
git clone https://github.com/gauravkatnoria12/The-Roast.git

# Open it
open index.html
```

That's the whole setup. ☕

---

## 📄 Page Sections

| Section | Vibe |
|---|---|
| **Loader** | Gold progress bar, italic logo reveal |
| **Hero** | Slow-zoom background, massive serif headline, scroll indicator |
| **Collector's Series** | Offset grid of 3 rare coffee product cards |
| **The Craft** | Two-column layout with stacked images + roasting process copy |
| **Heritage** | Full-viewport parallax-style image with a single quote overlaid |
| **Footer** | Minimal 3-column links + brand tagline |

---

## 📬 Get In Touch

Built by **Gaurav Katnoria**

📧 g200005k@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/gaurav-katnoria-78a4a33ab/)
🐙 [GitHub](https://github.com/gauravkatnoria12/)

---

## 📄 License

© 2026 Gaurav Katnoria. All rights reserved.

"The Roast" is a fictional brand created for portfolio purposes. Feel free to study the code and get inspired, but please build your own thing from scratch. ✌️

---

*Built for the Discerning.* 🥃

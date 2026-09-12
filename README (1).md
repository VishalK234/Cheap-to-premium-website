# Level Up — Upgrade This Website

A playful, single-page site that lets you "upgrade" a fake startup's website through six wildly different visual tiers — from a dead-broke Geocities-style page to a shimmering enterprise-grade design.

## Live Demo
https://vishalk234.github.io/Cheap-to-premium-website/

## Demo Video
https://www.kapwing.com/videos/6aa58885d982fa25829946ab

## Features
- **6 fully distinct visual tiers** (Dirt, Basic, Startup, Funded, Agency, Enterprise) — each with its own color palette, typography, spacing, and shadows, all driven by CSS custom properties
- **Zero page reloads** — tier switching is instant, powered by CSS `:has()` selectors reacting to radio button state
- **Flicker effect** on the free "Dirt" tier and an ambient animated gradient on the top "Enterprise" tier
- **Hidden Easter egg** — try clicking the site logo
- **Fully responsive** and respects `prefers-reduced-motion` for accessibility

## Tech Stack
- HTML5
- CSS3 (custom properties, `:has()` selector, animations, radio/checkbox-based state)

## Setup Instructions

No build tools or dependencies required — it's a single static HTML file.

1. Clone this repository:
   ```bash
   git clone https://github.com/VishalK234/Cheap-to-premium-website.git
   ```
2. Open the project folder:
   ```bash
   cd Cheap-to-premium-website
   ```
3. Open `index.html` directly in your browser:
   ```bash
   open index.html
   ```
   *(or just double-click the file)*

That's it — no npm install, no server needed.

## How to Use
1. Scroll to the **"Upgrade this website"** section.
2. Click through the six pricing tiers (Dirt → Enterprise) and watch the entire page — colors, fonts, spacing, and even copywriting — transform instantly.

## License
MIT — feel free to fork and remix.

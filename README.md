# Random Signal Web App

This ZIP contains a single-file web app to simulate BUY/SELL signals with multilingual UI and mobile/Telegram-friendly layout.

## Features
- Brokers, currency pairs (with **(OTC)**), timeframes.
- Language switcher: English, Русский, Español, Français, العربية.
- Stylish candlestick animation indicating BUY/SELL direction.
- **Sticky signal** per (broker + pair + timeframe): the signal stays the same for the entire timeframe.
- **Countdown timer**; buttons are disabled until the timeframe ends.
- Works on mobile and in Telegram WebView; uses `localStorage` to persist the active signal.

## How to run locally
Just open `index.html` in any modern browser — no server needed.

## One‑click deploy options
### GitHub Pages
1. Create a repository and upload `index.html` to the root.
2. Settings → Pages → Deploy from a branch, pick `main` and `/ (root)`.
3. Your site will be at `https://<username>.github.io/<repo>/`.

### Netlify
Drag & drop `index.html` (or this ZIP) into Netlify → **Add new site → Deploy manually**.

### Cloudflare Pages
Create a project → **Direct Upload** → drop `index.html` or the ZIP.

Deployed: 2025-08-14T15:00:25.017810Z

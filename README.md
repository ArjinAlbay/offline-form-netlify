# Offline Form - Netlify Integration

Contact form that works without internet connection and syncs with Netlify Forms when online.

## Features

- Works offline - forms saved locally
- Auto-sync when connection restored
- Email notifications via Netlify Forms

## Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yourusername/offline-form-netlify)

## Test Offline

1. Open Developer Tools (F12)
2. Network tab → "Offline"
3. Submit form
4. Go online - auto-sends

## How It Works

- **Online**: Direct to Netlify
- **Offline**: Saved in browser
- **Reconnect**: Auto-send pending forms

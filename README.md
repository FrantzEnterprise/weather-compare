# 🌤️ 3-City Weather Compare

A single-page weather application that displays weather for **3 cities side by side** for easy comparison.

## Features

- **3-column layout** — Compare weather conditions across any three cities simultaneously
- **Real-time data** — Powered by [OpenWeatherMap](https://openweathermap.org/) API
- **Live search** — Type any city names and hit Refresh or press Enter
- **Responsive** — Works on desktop, tablet, and mobile
- **No build step** — Just open `index.html` in any browser

## How to Use

1. Open `index.html` in a browser (or host it on any static server)
2. Enter city names in the three input fields
3. Click **Refresh Weather** or press **Enter**
4. See temperature, conditions, humidity, wind speed, and pressure for all three cities

## Default Cities

- London (UK)
- Tokyo (Japan)
- New York (USA)

## Tech Stack

- HTML + CSS + vanilla JavaScript (no frameworks)
- OpenWeatherMap API (free tier)
- Deployed as a static single-page app

## Deployment

Deploy anywhere that serves static files:

```bash
# Example: deploy using GitHub Pages
git push origin main
```

Then enable GitHub Pages in your repo settings → Source: `main` → root.

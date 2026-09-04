# Galaxy Tab Desk Dashboard

This folder contains a lightweight dashboard designed for the Samsung Galaxy Tab A 10.1 (2019) in landscape mode.

## What it includes
- Live clock/date
- Chicago current weather
- 4-day forecast
- Simple schedule area
- Simple to-do area
- Dark, tablet-friendly layout
- No Google account required
- No paid API key required (weather uses Open-Meteo)

## Easiest way to publish with GitHub Pages
1. Create a new public GitHub repository, for example: `desk-dashboard`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. GitHub will show your Pages URL after deployment.
7. Put that full URL into WallPanel Pro → **Dashboard URL**.

## WallPanel Pro settings
Recommended:
- Open On Device Boot: ON
- Browser Refresh: ON
- Network Disconnect: ON
- Hardware Acceleration: ON
- Use GeckoView: ON
- Ignore SSL Errors: OFF
- Theme: Dark
- Fullscreen: ON

## Editing your schedule/tasks
Open `index.html` and find the sections:
- `Today's Schedule`
- `To Do`

Replace the example rows with your own items.

## Weather location
The default coordinates are Chicago:
- Latitude: 41.8781
- Longitude: -87.6298

To change the location, edit `LAT`, `LON`, and `TZ` near the bottom of `index.html`.

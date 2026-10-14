# Isobar Weather

A free weather app that runs entirely in the browser. No API keys, no server, no build step.

- Forecasts from [Open-Meteo](https://open-meteo.com/) (CC BY 4.0)
- Severe weather alerts for US locations from the [National Weather Service](https://www.weather.gov/)
- Big 3D temperature and conditions that lean toward your finger and move with the weather: sun rays, drifting clouds, rain that splashes on the numbers, snow that settles on them, lightning, fog and wind
- More readings (humidity, UV, clouds, air quality, pressure, visibility, sunset) folded under **See more** on the main card
- A one-screen iPhone layout: drag the main card to move through time; drag the date slider on the Days tab, tap any hour, day, 3D block or metric cell, and detail opens in a bottom sheet
- A 3D field of the next 10 days that sways gently on its own and tilts up to 20° each way when you drag it, one block per hour (hours before the selected time turn see-through so the days behind stay visible), switchable between temperature, feels-like, rain, wind, humidity, UV, clouds and pressure
- Current conditions, a 2-hour rain outlook in 15-minute steps, 24-hour and 10-day forecasts, air quality
- City search, saved cities, use-my-location, °F/°C, and a forecast model picker (ECMWF, GFS, ICON, GEM)

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets the app install to a home screen |
| `apple-touch-icon.png` | iPhone home screen icon |
| `icon-192.png`, `icon-512.png` | Android and install icons |
| `favicon.png` | Browser tab icon |

## Publish with GitHub Pages

1. Upload all files to the root of this repository.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
3. After a minute or two the app is live at `https://<your-username>.github.io/<repo-name>/`.
4. On iPhone, open the link in Safari and tap **Share → Add to Home Screen**.

To update the app, upload a new `index.html`. It replaces the old one.

## Notes

Open-Meteo's free API is for non-commercial use. Saved cities and settings are stored in your browser only.

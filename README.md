# Haara (حارة) — Riyadh Heat Map

A minimalist, satellite-style live heat map of Riyadh showing real-time surface temperature and weather conditions across the city's districts.

## Features
- Live temperature data via [Open-Meteo](https://open-meteo.com/) (no API key required)
- 24-hour scrubber — drag through the day to see the thermal forecast play out
- District-level readouts: temperature, feels-like, humidity, wind, sky condition
- Extreme-heat alerts (NOW / forecast early-warning / scrub-triggered)
- Bilingual UI (English + Arabic)
- Dark, glassmorphism-inspired interface

## Live demo
https://m1sh7777.github.io/haara-riyadh-heat-map-/

## Tech
Single-file HTML/CSS/JS — no build step required. Deployable as a static site on GitHub Pages or Vercel.

## Data source
Weather data is powered by [Open-Meteo](https://open-meteo.com/), a free open-source weather API. Coverage reflects Open-Meteo's forecast grid resolution, so nearby districts may occasionally show identical readings. Readings are 2m air temperature, not satellite land surface temperature.

**Powered by [Open-Meteo.com](https://open-meteo.com/)**

made by mesh3al 

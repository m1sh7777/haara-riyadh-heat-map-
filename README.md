# Haara (حارة) Riyadh Heat Map

A live, minimalist style heat map of Riyadh showing temperature and weather across the city's districts.

## About this project

After finishing Harvard's CS50 Introduction to Computer Science, I wanted to see how full stack web development actually fits together. Haara is what came out of that.
I learned a lot about working with a live API, and making an app readable and accessible.

## Features
- Live temperature data via [Open-Meteo](https://open-meteo.com/) (no API key required)
- 24 hour scrubber: drag through the day to see the thermal forecast.
- District level readouts: temperature, simulated(feels like), humidity, wind, sky condition
- Extreme heat alerts (NOW, forecast early warning)
- Bilingual UI (English + Arabic)
- Dark, glassmorphism inspired interface

## Demo
https://m1sh7777.github.io/haara-riyadh-heat-map-/

https://haara-riyadh-heat-map.vercel.app/

## Program
Single file HTML/CSS/JS. Deployable on GitHub and Vercel.

## Data source
Weather data is powered by [Open-Meteo](https://open-meteo.com/), a free open source weather API. Coverage reflects Open-Meteo's forecast grid resolution, so nearby districts may occasionally show identical readings. Readings are 2m air temperature, not satellite land surface temperature.

**Powered by [Open-Meteo.com](https://open-meteo.com/)**

made by mesh3al 

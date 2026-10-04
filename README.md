# weather-station
A vanilla HTML, CSS, and JavaScript weather app styled like a live instrument panel. Detects your location or searches any city, then displays current conditions, wind and humidity gauges, and a 7-day forecast — with a color palette that shifts dynamically based on the actual weather (gold for sun, blue for rain, violet for storms, icy cyan for snow).

Live demo: https://sthitipragyan06.github.io/weather-station/

Features
Auto-detect location via the browser Geolocation API
City search with autocomplete-style suggestions (Open-Meteo Geocoding API)
Live current conditions — temperature, "feels like," humidity, wind speed
Custom SVG gauges for humidity and wind, no chart library required
7-day forecast log with daily highs, lows, and condition icons
Dynamic color theming — the entire UI's accent color changes based on live weather conditions (clear, cloudy, rain, snow, storm), and each day in the forecast is colored by its own condition
No API key required — powered by the free Open-Meteo API, so it's safe to deploy publicly with nothing to leak
Fully responsive, no frameworks, single HTML file
Tech Stack
HTML5
CSS3 (custom properties, dynamic theming via JS, SVG gauges)
Vanilla JavaScript (ES6+, fetch, Geolocation API)
Open-Meteo REST API for weather and geocoding
Google Fonts: Space Grotesk, JetBrains Mono, Inter
Getting Started
No installation or build tools required.

Clone the repo:
git clone https://github.com/SthitiPragyan06/weather-station.git
Open index.html in any modern browser.
That's it — the app runs entirely client-side and fetches live data from Open-Meteo.

Deploying with GitHub Pages
Push the repo to GitHub.
Go to Settings → Pages.
Under Source, select the main branch and /root.
Save. The app will be live at https://sthitipragyan06.github.io/weather-station/.
Project Structure
weather-station/
├── index.html   # markup, styles, and app logic (single file)
└── README.md
Possible Future Enhancements
Hourly forecast breakdown
Reverse geocoding to show a real place name for detected coordinates
Saved/favorite cities list
Unit toggle (°C / °F, km/h / mph)
Author
Sthiti Pragyan Mohapatra [GitHub](https://github.com/SthitiPragyan06)

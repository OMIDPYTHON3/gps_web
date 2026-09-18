# 🚗 GPS Live Dashboard

A real-time, mobile-first GPS dashboard with automotive-style gauge, compass, and live metrics.

## Features

- **Speed Gauge:** Animated SVG speedometer (0–180 km/h)
- **Compass:** Live heading with cardinal directions
- **Altitude Visualizer:** Gradient fill + dynamic line
- **Pulse Cards:** Subtle animation on every GPS update
- **Progress Meters:** Visual bars for accuracy, altitude, bearing
- **Dark/Light Theme:** Toggle with persistence
- **Mobile First:** Responsive layout, touch-friendly

## Tech Stack

- Pure HTML5 + CSS3 + Vanilla JavaScript
- Geolocation API (`navigator.geolocation.watchPosition`)
- No build step, no dependencies

## Usage

1. Open `gps_live.html` in a modern browser (Chrome, Firefox, Safari, Edge).
2. Grant location permission when prompted.
3. Tap **شروع GPS** to start tracking.

## Metrics Displayed

| Metric | Description |
|--------|-------------|
| Speed | Current speed in km/h and m/s |
| Max Speed | Peak speed in current session |
| Distance | Total distance traveled (session) |
| Altitude | GPS altitude in meters |
| Accuracy | Horizontal & vertical accuracy |
| Bearing | Direction of travel (0–360°) |
| Coordinates | Latitude & Longitude (7 decimals) |

## Privacy

All processing happens locally in your browser. No data is sent to any server.

## License

MIT © OMIDPYTHON3

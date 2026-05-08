# khairi-s-file

Simple real-time sensor dashboard built with HTML, JavaScript, and Chart.js.

## Run locally

1. Serve the repository root with any static server, for example:
   ```bash
   python3 -m http.server 8000
   ```
2. Open `http://localhost:8000/index.html`.
3. Ensure your API is available at `/api/sensor-data` and returns either:
   - A single object like `{ "temperature": 24.5, "humidity": 51, "timestamp": "2026-05-08T07:00:00Z" }`
   - Or an array of such objects (the latest item is used).

# Dijkstra Route Master

Browser-based gamified learning game for practicing Dijkstra's shortest path algorithm.

Players select the next minimum-cost frontier node, watch tentative distances update, receive immediate feedback, and complete routes across multiple graph sizes. Challenge mode tracks score, lives, accuracy, hints, shortest path results, and downloadable GPAF-style JSONL gameplay logs.

## Quick Run

Open `index.html` with a modern browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

The game uses CDN-hosted Three.js and Tailwind CSS, so an internet connection is recommended for first load.

# Audixa

Audixa is a lightweight, Spotify-inspired web music player built with vanilla HTML, CSS, and JavaScript. It provides a clean, responsive interface to browse curated playlists and stream audio tracks directly in the browser.

## Features

- **Spotify-Inspired UI:** Dark-themed interface featuring a sidebar library, playlist grid, and a bottom playback bar.
- **Dynamic Playlists:** Playlist metadata and song collections loaded dynamically from JSON data sources.
- **Audio Controls:** Play, pause, skip forward/backward, shuffle, and single-track loop.
- **Interactive Seek & Volume:** Progress bar with live duration tracking and an adjustable volume slider.
- **Keyboard Shortcuts:** Convenient keyboard controls for quick navigation:
  - `Space` or `K`: Play / Pause
  - `J`: Rewind 10 seconds
  - `L`: Forward 10 seconds
  - `Arrow Up` / `Arrow Down`: Adjust volume
- **Responsive Layout:** Adapts smoothly across desktop, tablet, and mobile screens with a collapsible sidebar drawer.

## Tech Stack

- **Frontend:** HTML5, CSS3 (CSS Variables, Flexbox, Media Queries)
- **Logic:** Vanilla JavaScript (ES6+, Fetch API, HTML5 Audio API)
- **Data:** JSON (`albums.json`, `songs.json`)
- **Media Hosting:** Cloudinary CDN

## Getting Started

1. Open the project folder in **VS Code**.
2. Right-click `index.html`.
3. Select **Open with Live Server**.

## Project Structure

```text
Audixa/
├── assets/          # SVG icons, logo, and playback indicators
├── css/
│   ├── style.css       # Core styling and player layout
│   ├── responsive.css  # Mobile and tablet responsiveness
│   └── utilities.css   # Theme colors and reusable utility classes
├── js/
│   ├── script.js       # Audio playback engine and UI event listeners
│   ├── shortcuts.js    # Keyboard navigation handler
│   ├── albums.json     # Playlist names, descriptions, and cover art
│   └── songs.json      # Track list categorized by playlist
└── index.html       # Main application markup
```

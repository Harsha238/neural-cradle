# Neural Cradle – Hand-Tracked String Art

Neural Cradle is an interactive browser-based visualization that transforms hand movements into a futuristic digital string-art experience using MediaPipe Hands and p5.js.

## Features

* Real-time hand tracking using MediaPipe Hands
* Supports tracking of both hands simultaneously
* Neon glowing finger joints and hand skeletons
* Dynamic Cat's Cradle string connections between fingertips
* Elastic string behavior based on hand distance
* Color transitions from Cyan → Magenta → Yellow
* Particle explosion effects when fingertips touch
* Futuristic HUD interface
* Webcam-based interaction with mirrored video feed
* Smooth real-time rendering optimized for modern browsers

## Technologies Used

* HTML5
* JavaScript
* p5.js
* MediaPipe Hands
* Canvas API

## How It Works

1. The browser requests webcam access.
2. MediaPipe detects and tracks 21 landmarks on each hand.
3. Hand landmarks are rendered as glowing neon points.
4. Dynamic strings connect matching fingertips across both hands.
5. String color and tension change as hands move apart.
6. Particle bursts are generated when fingertips from opposite hands touch.

## Installation

### Option 1: Open Directly

1. Download the project.
2. Open `index.html` in Google Chrome.
3. Allow camera access when prompted.

### Option 2: Run with Local Server

```bash
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

## Controls

* Show one hand to view hand tracking.
* Show both hands to activate Cat's Cradle strings.
* Touch fingertips together to trigger particle explosions.
* Move hands apart to increase string tension and color intensity.

## Project Structure

```text
index.html
```

The entire application is contained in a single HTML file.

## Future Enhancements

* Laser-beam string effects
* Hand silhouette glow
* Cyberpunk background themes
* Audio-reactive visualizations
* Gesture-based interactions

## License

This project is open source and available for educational and personal use.

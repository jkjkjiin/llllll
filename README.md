# Piupiu Starship - HTML5 Canvas Game

## Overview
This is a space-themed Asteroids-style game built with vanilla HTML5, CSS, and JavaScript. Players defend their planet by shooting at incoming asteroids. The game features canvas-based rendering and interactive gameplay.

## Project Type
Static frontend website - pure HTML/CSS/JavaScript with no build system or dependencies.

## Technologies Used
- HTML5 Canvas for game rendering
- Vanilla JavaScript for game logic
- CSS for styling
- Python's built-in HTTP server for serving static files

## Project Structure
```
.
├── index.html          # Main HTML file with game structure
├── css/
│   └── style.css       # Game styles and UI
├── js/
│   ├── main.js         # Core game logic and classes
│   └── dwl.js          # Additional JavaScript utilities
└── img/                # Game assets (sprites, backgrounds)
    ├── asteroid.webp
    ├── background.png
    ├── logo.png/webp
    ├── planet.webp
    └── player.webp
```

## Running the Game
The game is served using Python's built-in HTTP server on port 5000:
```bash
python -m http.server 5000 --bind 0.0.0.0
```

The workflow is already configured to run this automatically.

## Deployment
Configured for Replit autoscale deployment:
- Deployment target: autoscale (perfect for static websites)
- Run command: `python -m http.server 5000 --bind 0.0.0.0`
- No build step required

## Game Features
- Player controls a ship orbiting a planet
- Shoot asteroids to protect the planet
- Lives system
- Score tracking
- Responsive canvas rendering

## Recent Changes
- **2025-10-02**: Initial Replit environment setup
  - Installed Python 3.11 for HTTP server
  - Configured workflow to serve static files on port 5000
  - Set up deployment configuration for autoscale
  - Created .gitignore for Python and Replit files

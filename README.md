# Tilting Game

![Gameplay screenshot](./Screenshot%202024-12-26%20234501.png)

A simple, lightweight browser game built with HTML, CSS, and JavaScript. Tilt or move the board to guide an object through obstacles, collect points, and reach the goal. Great as a small project for learning vanilla web game mechanics.

## Table of contents
- [Demo](#demo)
- [How to play](#how-to-play)
- [Controls](#controls)
- [Features](#features)
- [Tech stack](#tech-stack)
- [Run locally](#run-locally)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Demo
Open `index.html` in your browser (double-click or serve with a static server). The screenshot above shows a gameplay frame.

## How to play
Tilt your device or use the keyboard/mouse controls to move the game object. Navigate through levels, avoid hazards, collect targets to score points, and try to reach the goal.

## Controls
- Mobile: Tilt the device (uses DeviceOrientation where supported).
- Desktop: Arrow keys (← ↑ → ↓) or WASD to simulate tilt/movement.
- Mouse: Click-and-drag or move the mouse if implemented.

If your implementation uses different inputs, adjust the instructions accordingly.

## Features
- Device tilt support for mobile
- Keyboard controls for desktop
- Score tracking and simple physics-based movement
- Responsive layout for different screen sizes

## Tech stack
- JavaScript — game logic
- HTML — structure
- CSS — styles and responsive layout

Languages in this repo (approx.): JavaScript, CSS, HTML.

## Run locally
1. Clone the repo:
   ```bash
   git clone https://github.com/BinaryVortex/Tilting-Game.git
   ```
2. Change into the project directory:
   ```bash
   cd Tilting-Game
   ```
3. Open the game in your browser:
   - Double-click `index.html`, or
   - Start a simple static server (recommended for some browsers):
     - Python 3: `python -m http.server 8000`
     - Then open `http://localhost:8000` in your browser.

## Troubleshooting
- If tilt controls don't work on desktop, try using the arrow keys or enable device emulation of orientation in your browser devtools.
- Some browsers block DeviceOrientation events on insecure origins — if tilt doesn't respond on mobile, try hosting over HTTPS or enabling motion sensors in browser settings.

## Contributing
Contributions, bug reports, and suggestions are welcome!
1. Fork the repository
2. Create a branch for your change (`git checkout -b feature/my-change`)
3. Commit your changes and open a pull request with a clear description

If you'd like, I can open a PR for larger changes or add issues for tracked improvements.

## License
Add a license (e.g., MIT) if you want this project to be open source. If unsure, MIT is a permissive, commonly used license.

## Credits
Created by BinaryVortex — a small project built using vanilla web technologies.

# Pac-Man Web Game

A modern browser-based recreation of the classic **Pac-Man** arcade game.  
Built entirely with **HTML5 Canvas**, **CSS**, and **vanilla JavaScript**—no frameworks.

---

## Overview
This project reproduces the original Pac-Man experience while demonstrating core web-development and game-programming skills:

* **Smooth keyboard controls** (Arrow keys / WASD).
* **Intelligent Ghost AI** – ghosts use a shortest-path algorithm to chase Pac-Man.
* **Collision detection** for walls, pellets, and ghosts.
* **Scoring and lives system** displayed in real time.
* Classic **sound effects** including the “waka-waka” pellet chomp.

The complete development process, from research to testing, is documented in  
[`PacmanProjectReport.pdf`](docs/PacmanProjectReport.pdf).

---

## Features
* **HTML5 Canvas Rendering** – all visuals drawn directly to the canvas.
* **Game Loop Architecture** – 30 FPS rendering and state updates handled in `game.js`.
* **Pac-Man & Ghost Classes** – modular ES6 classes (`pacman.js`, `ghost.js`) for movement, animation, and AI.
* **Dijkstra-style Pathfinding** – ghosts dynamically calculate the shortest route toward Pac-Man.
* **Responsive Browser Play** – works in Chrome, Firefox, Edge, and Safari with no build tools.

---

## Repository Structure

├── index.html # Main page and canvas setup
├── style.css # Optional CSS styling (if included)
├── game.js # Game loop, map, collision logic, scoring
├── pacman.js # Pac-Man class: movement, animation, pellet eating
├── ghost.js # Ghost class: AI pathfinding and movement
├── assets/
│ ├── animations.gif # Pac-Man animation frames
│ ├── ghost.png # Ghost sprite sheet
│ └── sounds/
│ └── waka.mp3 # Pellet sound effect
└── docs/
├── PacmanProjectReport.pdf # Full technical report & testing


---

## How to Run
1. **Clone or download** this repository.
2. Open `index.html` in any modern web browser.
3. Use **Arrow keys** or **WASD** to move Pac-Man.
4. Eat all pellets to win while avoiding the ghosts.

_No build step or server required._

---

## Skills Demonstrated
* **Front-End Web Development** – HTML5 Canvas graphics and responsive layout.
* **JavaScript Game Programming** – real-time rendering, collision detection, state management.
* **Artificial Intelligence** – Dijkstra-based pathfinding for adaptive enemy behaviour.
* **Software Engineering** – modular code structure, documentation, and testing.

---

## Future Enhancements
* Complete **power-pellet** mode (ghosts turn blue and flee).
* Add mobile touch controls and multiple maze layouts.
* Improve audio and background music.

* Note : I have other major projects I'd like to accomplish before I come back to finish this in the future. 

---

Developed as an **Individual Computing Project** to showcase strong programming,
problem-solving, and documentation skills.


Pritam Gurung 

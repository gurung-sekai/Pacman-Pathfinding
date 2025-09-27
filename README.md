# Pac‑Man Web Game

A modern browser-based recreation of the classic **Pac‑Man** arcade game.  
Built entirely with **HTML5 Canvas**, **CSS**, and **vanilla JavaScript** — no frameworks.

![animations](https://github.com/user-attachments/assets/272f6cdd-2a50-417a-b74d-60d1f1721d90)
<img width="300" height="236" alt="ghost" src="https://github.com/user-attachments/assets/9949cdf9-58f0-4777-a3d8-8021e714702b" />

---

## Overview
This project faithfully reproduces the original Pac‑Man experience while demonstrating core **front‑end development** and **game‑programming** skills:

* Smooth keyboard controls (Arrow keys / WASD)
* Intelligent Ghost AI using a shortest‑path algorithm
* Collision detection for walls, pellets, and ghosts
* Scoring and lives system displayed in real time
* Classic “waka‑waka” pellet‑chomp sound effects

The full development process, from research through testing, is documented in  
[`PacmanProjectReport.pdf`](Pacman/PacmanProjectReport.pdf)  
Presentation slides: [`PacmanPresentation.pdf`](docs/presentation.pdf)

---

## Features
* **HTML5 Canvas Rendering** – all visuals drawn directly to the canvas
* **Game Loop Architecture** – 30 FPS rendering and state updates handled in `game.js`
* **Pac‑Man & Ghost Classes** – modular ES6 classes (`pacman.js`, `ghost.js`) for movement, animation, and AI
* **Dijkstra‑style Pathfinding** – ghosts dynamically calculate the shortest route toward Pac‑Man
* **Responsive Browser Play** – works in Chrome, Firefox, Edge, and Safari with no build tools

<img width="490" height="520" alt="gameplay image" src="https://github.com/user-attachments/assets/9d5a4809-0e7c-4c0f-bcb4-6133eb8afe1f" />

---

## Gameplay Screenshots and Live Demonstration

<img width="582" height="656" alt="live gameplay" src="https://github.com/user-attachments/assets/a5979212-5ead-45ac-b1e3-3cddcdeaa60d" />

https://github.com/user-attachments/assets/36dddcd2-44a9-4118-9e2d-feb4fd61b7cd

---

## Repository Structure
```
├── index.html              # Main page and canvas setup
├── game.js                 # Game loop, map, collision logic, scoring
├── pacman.js               # Pac‑Man class: movement, animation, pellet eating
├── ghost.js                # Ghost class: AI pathfinding and movement
├── assets/
│   ├── animations.gif      # Pac‑Man animation frames
│   ├── ghost.png           # Ghost sprite sheet
│   └── sounds/
│       └── waka.mp3        # Pellet sound effect
└── docs/
    ├── PacmanProjectReport.pdf  # Full technical report & testing
    └── presentation.pdf         # Slide deck
```

---

## How to Run
1. **Clone or download** this repository.
2. Open `index.html` in any modern web browser.
3. Use **Arrow keys** or **WASD** to move Pac‑Man.
4. Eat all pellets to win while avoiding ghosts.

_No build step or server required._

---

## Skills Demonstrated
* **Front‑End Web Development** – HTML5 Canvas graphics and responsive layout
* **JavaScript Game Programming** – real-time rendering, collision detection, state management
* **Artificial Intelligence** – Dijkstra-based pathfinding for adaptive enemy behaviour
* **Software Engineering** – modular code structure, documentation, and testing

<img width="490" height="526" alt="additional gameplay" src="https://github.com/user-attachments/assets/346efcbd-8f85-4112-91e1-488a73efa813" />

---

## Future Enhancements
* Complete **power‑pellet** mode (ghosts turn blue and flee)
* Add mobile touch controls and multiple maze layouts
* Improve audio and background music

*Note: I have other major projects to pursue before returning to finish these enhancements.*

---

Developed as an **Individual Computing Project** and **Project Competition**  
to showcase strong programming, problem‑solving, and documentation skills.

**Author:** Pritam Gurung

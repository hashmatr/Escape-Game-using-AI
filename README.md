# AI-Powered Escape Room Game

## Overview
This project is an **AI-powered escape room game** developed using **Python and Pygame**. The game features AI-controlled enemies, player navigation, and procedural level parsing. The AI uses **A* search and BFS** for movement and decision-making.

## Features
- **AI-Powered Navigation**
  - Uses **A* search** for pathfinding
  - Implements **BFS for enemy movement**
  - Dynamic enemy behavior and avoidance strategies

- **Interactive Gameplay**
  - Player can collect keys to unlock doors
  - Enemies patrol and chase the player
  - Hazards like spikes cause level resets

- **Procedural Level Parsing**
  - Reads levels from JSON files
  - Loads and scales tile-based graphics
  - Supports multiple levels

## Technologies Used
- **Programming Language:** Python
- **Game Engine:** Pygame
- **Algorithms Implemented:**
  - **A* Search** for pathfinding
  - **BFS for enemy AI movement**
  - **Collision Detection & Path Planning**

## Project Structure
```
📂 AI Escape Room Game
├── 📜 main.py                # Main game loop
├── 📜 ai.py                  # AI logic for pathfinding and decision-making
├── 📜 tempCodeRunnerFile.py   # Temporary execution file (can be ignored)
├── 📂 assets/                # Game assets (images, levels)
│   ├── lvl1.json             # Level 1 data
│   ├── lvl2.json             # Level 2 data
│   ├── ...                   # More levels
│   ├── agent.png             # Player sprite
│   ├── tileset.png           # Game tileset
└── 📜 README.md              # Project documentation
```

## Installation & Setup
### Prerequisites
- **Python 3.x** installed
- **Pygame** installed (`pip install pygame`)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-escape-room.git
   ```
2. Run the game:
   ```bash
   python main.py
   ```

## How to Play
1. **Start the game** using `python main.py`.
2. Use **arrow keys** to navigate the player.
3. Collect **keys** to open locked doors.
4. Avoid **enemies and spikes** to survive.
5. Press **'A'** to enable AI control (AI will play automatically).
6. Complete all levels to win the game!

## Contributors
- **Hashmat Raza**

## License
This project is licensed under the **MIT License**.

---
> *An AI-powered game combining pathfinding and dynamic level progression!*


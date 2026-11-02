# 🐍 Koi Snake – Phaser 3

A colorful, neon-themed Snake arcade game built using **JavaScript and Phaser 3**. Control a cute snake, collect food, grow longer, earn bonus points, and beat your highest score!

Featuring smooth movement, glowing visual effects, particle animations, golden apple bonuses, and keyboard and touch controls.

## ✨ Features

- 🐍 **Classic Snake Gameplay:** Control the snake and collect food to grow.
- 💖 **Cute Visual Design:** Neon colors, glowing effects, heart-shaped food, and animated snake eyes.
- ⭐ **Golden Apple Bonus:** A golden bonus appears after every 5 food items and stays for 6 seconds.
- ⚡ **Progressive Difficulty:** The snake gets faster as you collect more food.
- 🎨 **Particle Effects:** Animated sparkles and particle bursts when collecting food and bonuses.
- 🏆 **High Score System:** Automatically saves your best score using browser Local Storage.
- ⏸️ **Pause and Resume:** Pause and continue gameplay whenever needed.
- 📱 **Touch Controls:** Swipe to control the snake on touch-screen devices.
- ⌨️ **Keyboard Controls:** Supports arrow keys and WASD.
- 💥 **Collision Detection:** Detects wall collisions and self-collisions.
- 🔄 **Restart Gameplay:** Start a fresh game after game over.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Game structure |
| CSS3 | Page styling |
| JavaScript (ES6+) | Game logic |
| Phaser 3.80.1 | 2D game engine and rendering |
| Local Storage API | Persistent high-score storage |

## 🎮 Controls

| Key / Input | Action |
|---|---|
| ↑ / W | Move Up |
| ↓ / S | Move Down |
| ← / A | Move Left |
| → / D | Move Right |
| SPACE | Start / Resume |
| P | Pause / Resume |
| Swipe | Change direction on touch screens |

## 🍎 Bonus System

The game includes a special golden apple reward system.

- A golden apple appears after every 5 normal food items collected.
- Golden apples remain available for 6 seconds.
- Collecting a golden apple increases the score and adds 3 extra growth segments.
- Missing the golden apple causes it to disappear.

## ⚡ Difficulty System

The game gradually increases its speed as the player collects food.

| Parameter | Value |
|---|---|
| Starting movement delay | 140 ms |
| Minimum movement delay | 60 ms |
| Speed reduction per normal food | 3 ms |
| Golden apple appearance | Every 5 foods |
| Golden apple lifetime | 6 seconds |

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Google Chrome, Firefox, Edge, etc.).
- Internet connection to load Phaser 3.80.1 from the CDN.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/koi-snake-phaser.git
```

**2. Navigate to the project directory**

```bash
cd koi-snake-phaser
```

**3. Run the game**

Open `index.html` in your web browser.

Alternatively, use the VS Code Live Server extension and select **Open with Live Server**.

## 📂 Project Structure

```text
koi-snake-phaser/
│
├── index.html       # Main game implementation
├── README.md        # Project documentation
└── .gitignore       # Git ignored files
```

## 🧠 Game Mechanics

The game uses a grid-based movement system.

- The board consists of 20 × 20 cells.
- Each cell measures 24 × 24 pixels.
- The snake moves in four directions.
- Direction changes are buffered to preserve quick key inputs.
- Reverse-direction movement is prevented.
- Food and bonus positions are randomly generated in unoccupied cells.
- Collision detection determines when the game ends.

## 🔮 Future Improvements

- Add multiple difficulty modes.
- Introduce different food types and power-ups.
- Add background music and sound effects.
- Add multiple snake skins.
- Introduce leaderboard functionality.
- Add a start menu and settings screen.
- Improve mobile UI and gameplay responsiveness.

## 👨‍💻 Author

**YOUR NAME**

GitHub: [Gargi4-git](https://github.com/Gar gi4-git)

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

⭐ If you enjoyed playing Koi Snake, consider giving this repository a star!
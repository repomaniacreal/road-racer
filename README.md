# 🏎️ Road Runner

A simple endless racing game built with **HTML, CSS, and Vanilla JavaScript**.

The player controls a car, avoids obstacles, collects bonuses, and tries to achieve the highest possible score. The game progressively becomes faster and can trigger different power-ups during gameplay.

## ✨ Features

* 🏎️ Endless road racing gameplay
* 🚗 Player car movement
* 🚧 Random obstacles
* 💥 Collision detection
* 📈 Increasing game speed
* 🏆 Score system
* ⚡ Progressive difficulty
* 🚀 Nitro Boost
* 🛡️ Shield
* ✖️ 2X Score multiplier
* 🎮 Keyboard controls
* 📱 Responsive layout
* 🔓 No login required
* 💾 No database required
* ⚙️ Pure HTML, CSS, and JavaScript

## 🛠️ Tech Stack

* **HTML5**
* **CSS3**
* **Vanilla JavaScript**
* No framework
* No backend
* No database
* No build tool required

## 📁 Project Structure

```text
road-runner/
├── index.html
├── style.css
├── script.js
└── README.md
```

> The exact structure may differ depending on the current version of the project.

## 🚀 Installation

### 1. Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
```

Example:

```bash
git clone https://github.com/username/road-runner.git
```

### 2. Enter the project directory

```bash
cd road-runner
```

### 3. Run the game

Because this project uses plain HTML, CSS, and JavaScript, **no package installation is required**.

You can simply open:

```text
index.html
```

in your browser.

### Recommended: Use a local development server

If you use VS Code, install the **Live Server** extension and click:

```text
Open with Live Server
```

Alternatively, you can use Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## 🎮 Controls

| Key     | Action                      |
| ------- | --------------------------- |
| `←`     | Move left                   |
| `→`     | Move right                  |
| `↑`     | Move up / accelerate        |
| `↓`     | Move down / brake           |
| `Space` | Activate available power-up |
| `P`     | Pause / Resume              |

> Controls may vary depending on the current implementation.

## ⚡ Power-Ups

During gameplay, special bonuses can appear as the game progresses.

### 🚀 Nitro Boost

Increases the player's speed temporarily.

```text
+NITRO BOOST!
```

### 🛡️ Shield

Protects the player from a collision for a limited duration.

```text
SHIELD ONLINE
```

### ✖️ 2X Score

Doubles the score gained for a limited period.

```text
2X SCORE ACTIVATED
```

More power-ups can be added in the future.

## 📈 Game Progression

The game does not have a fixed maximum speed.

As the player survives longer:

```text
Time
  ↓
Game Speed ↑
  ↓
Difficulty ↑
  ↓
Obstacle Frequency ↑
  ↓
Score Multiplier / Bonuses
```

The goal is to survive as long as possible and achieve the highest score.

## 🏆 Scoring

The player's score increases while surviving on the road.

Additional score bonuses may be provided by power-ups such as:

* `2X SCORE`
* Avoiding obstacles
* Distance travelled
* Other future bonuses

## 📱 Responsive Design

The game is designed to work on different screen sizes, including:

* Desktop
* Laptop
* Tablet
* Mobile

For the best gameplay experience, a desktop browser with keyboard controls is recommended.

## 🌐 Browser Support

The game should work on modern browsers that support standard HTML5 and JavaScript APIs.

Recommended browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

## 🔧 Development

No dependencies are required.

There is no:

```text
npm install
```

or:

```text
npm run build
```

required for the basic version.

Simply edit the source files and refresh the browser.

### Main files

#### `index.html`

Contains the game interface and HTML structure.

#### `style.css`

Contains:

* Game layout
* Road styling
* Player styling
* Obstacles
* Power-up UI
* Animations
* Responsive styling

#### `script.js`

Contains the game logic, including:

* Game loop
* Player movement
* Collision detection
* Obstacle generation
* Speed progression
* Score calculation
* Power-ups
* Game state
* Restart functionality

## 🐛 Troubleshooting

### Game does not start

Make sure JavaScript is enabled in your browser.

If you are opening the project directly using `file://`, try using a local server instead:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

### Keyboard controls do not work

Click inside the game window first and make sure the browser page has focus.

### Changes are not appearing

Try a hard refresh:

```text
Mac:     Cmd + Shift + R
Windows: Ctrl + Shift + R
```

## 🚧 Future Improvements

Possible improvements:

* [ ] Mobile touch controls
* [ ] Sound effects
* [ ] Background music
* [ ] More obstacle types
* [ ] More power-ups
* [ ] Car customization
* [ ] Multiple road environments
* [ ] Day/night system
* [ ] Leaderboard
* [ ] Local high-score storage
* [ ] More visual effects
* [ ] Difficulty levels
* [ ] Multiplayer mode

## 📄 License

This project is for learning and demonstration purposes.

If you want to use, modify, or redistribute this project, check the repository license before doing so.

---

## 👨‍💻 Author

**Zayyid**

Built with ❤️ using HTML, CSS, and JavaScript.

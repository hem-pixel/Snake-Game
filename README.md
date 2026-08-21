# 🐍 Snake Game

A simple and interactive **Snake Game** developed using Python.
The player controls the snake, collects food, increases the score, and tries to achieve the highest possible score without hitting the walls or the snake's own body.

## 🎮 About the Project

The **Snake Game** is a classic arcade game recreated using Python.

The objective is simple:

* 🐍 Control the snake
* 🍎 Eat the food
* 📈 Increase your score
* 🚧 Avoid hitting the walls
* 💥 Avoid hitting the snake's own body
* 🏆 Try to achieve the highest score

## ✨ Features

* 🎮 Keyboard-based controls
* 🍎 Random food generation
* 📊 Real-time score tracking
* 🐍 Snake growth after eating food
* 💥 Collision detection
* 🔄 Game restart functionality
* ⚡ Smooth gameplay
* 🖥️ Simple and user-friendly interface

## 🛠️ Technologies Used

* **Python 3.x**
* **Pygame**

## 📦 Installation

Make sure Python is installed on your system.

Install the required Pygame library using:

```bash
pip install pygame
```

## 📂 Project Structure

```text
Snake-Game/
│
├── snake_game.py
├── README.md
└── LICENSE
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Snake-Game.git
```

### 2. Navigate to the Project Folder

```bash
cd Snake-Game
```

### 3. Install Pygame

```bash
pip install pygame
```

### 4. Run the Game

```bash
python snake_game.py
```

## 🎮 Controls

| Key            | Action     |
| -------------- | ---------- |
| ⬆️ Up Arrow    | Move Up    |
| ⬇️ Down Arrow  | Move Down  |
| ⬅️ Left Arrow  | Move Left  |
| ➡️ Right Arrow | Move Right |

## 🧠 Game Logic

The game continuously performs the following steps:

```text
Start Game
    ↓
Create Snake
    ↓
Generate Food
    ↓
Read Keyboard Input
    ↓
Move Snake
    ↓
Check Collision
    ↓
Eat Food?
   ↙   ↘
 Yes    No
 ↓       ↓
Grow    Continue
Snake
   ↓
Update Score
   ↓
Continue Game
```

The game ends when the snake:

* Hits the game boundary
* Collides with its own body

## 📊 Scoring

Every time the snake eats the food:

```text
Score = Score + 1
```

As the score increases, the snake grows longer, making the game more challenging.

## 🎯 Learning Objectives

This project helps demonstrate practical Python programming concepts including:

* Variables and Data Types
* Functions
* Loops
* Conditional Statements
* Lists
* Event Handling
* Collision Detection
* Random Number Generation
* Game Development Basics
* Object Movement

## 🔮 Future Improvements

Possible improvements for future versions:

* 🏆 High-score system
* 🎵 Background music and sound effects
* 🎨 Multiple themes
* ⚡ Increasing difficulty
* ⏸️ Pause and Resume option
* 🏅 Different game levels
* 💾 Save high scores
* 🎮 Customizable controls
* 🌐 Online leaderboard

## 📸 Screenshots

Add your game screenshots here:

```text
screenshots/
├── gameplay.png
├── game-over.png
└── main-menu.png
```

Example:

![Snake Game Screenshot](screenshots/gameplay.png)

## 👨‍💻 Author

**Hemanth D**

Built with ❤️ and Python 🐍

## ⭐ Support

If you enjoyed this project, consider giving the repository a ⭐ on GitHub!

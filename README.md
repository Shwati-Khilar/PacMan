# 👾 Pac-Man Java Game

Welcome to **Pac-Man in Java**—a classic arcade remake with a modern twist! This project brings the nostalgia of Pac-Man to your desktop, complete with ghosts, food pellets, sound effects, and a retro look. Whether you're a gamer or a Java enthusiast, this project is both fun to play and easy to explore.

## 🎮 Introduction

This project is a faithful recreation of the iconic Pac-Man game, built entirely using Java and Swing. Navigate the maze, avoid ghosts, collect food, and aim for the high score!

## ✨ Features

* **Classic Gameplay:** Move Pac-Man through the maze, eat all the food, and avoid ghosts.
* **Multiple Ghosts:** Blue, orange, pink, and red ghosts each with unique behaviors.
* **Sound Effects:** Enjoy classic chomp and game over sounds.
* **Teleport Tunnels:** Warp from one side of the maze to the other.
* **High Score Tracking:** Try to beat your previous best!
* **Lives System:** You have 3 lives—make them count!
* **Simple Controls:** Use arrow keys to move Pac-Man.
* **Easy Restart:** Game restarts automatically after game over.


## 🚀 Installation

1. **Clone the Repository**
```bash
  git clone https://github.com/yourusername/pacman-java.git
  cd pacman-java
```
2. **Compile the Code**
```bash
  javac App.java PacMan.java
```
3. **Ensure Resources Are Present**
- Place all required images (`wall.png`, `pacmanUp.png`, `blueGhost.png`, etc.) and sound files (`chomp.wav`, `gameover.wav`) in the project directory.
4. **Run the Game**
```bash
  java App
```
## 🕹️ Usage

* **Start the Game:** Run the program. Instructions will pop up automatically.
* **Move Pac-Man:** Use the arrow keys (↑, ↓, ←, →).
* **Eat Food:** Guide Pac-Man over white dots to score points.
* **Avoid Ghosts:** Colliding with a ghost costs a life.
* **Teleport:** Use the tunnel in row 9 to warp across the maze.
* **Restart:** After game over, press any arrow key to restart.

## ⚙️ Requirements

* **Java JDK 8 or higher**
* **Swing GUI library** (included in standard Java)
* **Sound support** (Java Sound API)
* **Resource Files:** Ensure all `.png` and `.wav` files are present in the project directory.
  
## 📦 File Structure

| File               | Purpose                          |
|--------------------|----------------------------------|
| `App.java`         | Main entry point                 |
| `PacMan.java`      | Game logic and rendering         |
| `*.png`            | Game sprites (walls, ghosts, etc.)|
| `*.wav`            | Sound effects                    |


## ❓ FAQ
* **Q: How do I restart the game after losing?**
- A: Press any arrow key to restart after a game over.

* **Q: Can I customize the maze or add new features?**
- A: Absolutely! Modify the `tileMap` array or add new images and logic.

## 🧩 API & Customization

* **Maze Layout:** Edit the `tileMap` string array in `PacMan.java` to change the maze.
* **Sprites:** Replace `.png` files to use your own graphics.
* **Sounds:** Swap out `.wav` files for custom sound effects.
* **Game Speed:** Adjust the timer interval in `PacMan()` for faster or slower gameplay.
   

# Flappy Bird 🎮🐤

This is a Flappy Bird clone implemented in Java using Swing. The game features a flying bird that must navigate through randomly placed pipes without colliding. The longer you stay alive, the higher your score!

## 📸 Game Preview

> 🚧

## 📁 Project Structure
FlappyBird/
├── App.java # Main class to launch the game
├── FlappyBird.java # Game logic and rendering
├── flappybird.png # Bird sprite
├── flappybirdbg.png # Background image
├── toppipe.png # Top pipe image
└── bottompipe.png # Bottom pipe image

## ▶️ How to Play

- **Press the Spacebar** to make the bird flap upward.
- Avoid hitting the **pipes** or falling off the screen.
- Score increases by 1 for each pair of pipes successfully passed.
- Game ends on collision.
- **Press the Spacebar** again after a game over to restart.

## 🛠️ How to Run

1. **Make sure you have Java installed.** (Java 8+)
2. Place all files including the image assets (`flappybird.png`, `flappybirdbg.png`, `toppipe.png`, `bottompipe.png`) in the same directory as the `.java` files.
3. Compile the game:
   ```bash
   javac App.java FlappyBird.java

## 📦 Dependencies
No external libraries. This project uses only core Java libraries (javax.swing, java.awt, etc.).

## 🧠 Features
Real-time gameplay loop at 60 FPS

Random pipe generation with consistent gaps

Collision detection between the bird and pipes

Game restart after game over

Score tracking and display

## 📌 Notes
The game runs at a fixed window size of 360x640 pixels.

All images are loaded via relative paths using getClass().getResource(...). Ensure image files are in the root of the classpath (i.e., the same directory as the compiled .class files).

Designed for desktop environments with keyboard support.

## ✍️ Author
Jake Simonsen

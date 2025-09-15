# Boo The Blue Bob

An endless auto-runner adventure game built with the Godot Engine. Help Boo jump over obstacles, collect coins, and reach the finish line!


---

## 📜 About The Game

**Boo The Blue Bob** is a fast-paced 2D platformer that challenges your reflexes. [cite_start]In this game, the player character moves forward automatically, and your goal is to time your jumps perfectly to avoid obstacles and collect coins[cite: 10, 13]. [cite_start]The game was built using Godot and features procedural obstacle generation, dynamic UI, and a parallax background for a sense of depth[cite: 8, 16, 20, 25].

---

## ✨ Features

* [cite_start]**Endless Auto-Runner Gameplay**: The character moves forward automatically, so you can focus on the action[cite: 10].
* **Simple One-Button Controls**: Easy to learn, difficult to master. [cite_start]The only control you need is jump[cite: 13]!
* [cite_start]**Procedural Obstacle Spawning**: The game generates `redBlob` obstacles as you play, making each run unique[cite: 8].
* [cite_start]**Dynamic UI**: On-screen labels track your HP and collected coins in real-time as you play[cite: 16, 25].
* [cite_start]**Parallax Background**: Multiple background layers scroll at different speeds, creating a beautiful and immersive sense of depth[cite: 20].

---

## 🎮 How to Play

Based on the provided game scripts, this is an **auto-runner**. The character moves forward on their own.

* [cite_start]Press **Enter** or **Space** (`ui_accept` action) on the title screen to start the run[cite: 10].
* [cite_start]Press your **`jump`** key (configured in `Project > Project Settings > Input Map`, likely the **Space Bar**) to jump over obstacles[cite: 13].

> **Note on Movement**: Your request mentioned `Arrow Keys` for movement. [cite_start]The current `Map.gd` script only implements forward auto-running and does not use left/right input[cite: 10]. To add player-controlled movement, the `_physics_process` function in the player's script would need to be modified to handle horizontal input.

---

## 🎯 Gameplay Objective

* **Win Condition**: The main goal is to collect **3 coins**. [cite_start]Doing so will display the "Game Finished" screen[cite: 19].
* **Lose Condition**: The game is over if you collide with an obstacle. [cite_start]This will immediately trigger the game over screen and pause the game[cite: 8].

---

## 🚀 Getting Started

To run this project on your local machine, you'll need to have the Godot Engine installed.

### Prerequisites

* **Godot Engine** (Version 4.x recommended). You can download it from the [official Godot website](https://godotengine.org/).

### Installation & Setup

1.  **Clone the repository** to your local machine.
2.  **Open the Godot Engine** project manager.
3.  Click the **"Import"** button.
4.  Navigate to the cloned project folder and select the `project.godot` file.
5.  Once imported, select the project from the list and click **"Edit"**.
6.  Inside the editor, press the **F5** key (or the "Play" button) to run the main scene.

---

## 📁 Project Structure

* [cite_start]**/Scenes**: Contains all the main game levels, obstacles (`redBlob.tscn`), and character scenes (`Player.tscn`)[cite: 1, 8].
* [cite_start]**/Script**: Holds all the GDScript (`.gd`) files that control the game logic, including `Map.gd` (main loop) and `Player.gd` (player controller)[cite: 8, 11].
* [cite_start]**/SideScroller**: Contains core assets related to the player, including sprites like `Madeline_Idle.png`[cite: 1].
* [cite_start]**/Images**: Contains environmental assets like the ground sprite (`G.png`) and parallax background layers[cite: 7, 20].
* [cite_start]**UI Scripts**: `GameOver.gd`, `GameFinished.gd`, `Label.gd`, and `Label2.gd` control the various text labels on the screen[cite: 4, 17, 14, 23].

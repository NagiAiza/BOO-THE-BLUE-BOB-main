Of course. Here is the complete README for your project, with the formatting cleaned up as you requested.

Boo The Blue Bob
A multi-genre adventure game built with the Godot Engine. Explore a charming world, engage in dialogue-driven quests, and conquer challenging side-scrolling platformer levels.

📜 About The Game
Boo The Blue Bob is an ambitious 2D adventure that blends multiple gameplay styles. Players will begin in a top-down world, exploring areas, collecting items, and interacting with a cast of characters like a mysterious sorcerer and a cynical thief. The game features a complete dialogue system with animated text, driving a story with simple quests. After proving your worth by collecting enough gems, you will unlock challenging side-scrolling platformer levels where your reflexes and combat skills will be put to the test.

✨ Features
Dual Gameplay Modes: Seamlessly transition between top-down exploration and classic side-scrolling platforming.

Interactive Dialogue System: A powerful, centralized dialogue manager delivers conversations with an animated "typewriter" effect.

Quest-Driven Progression: Engage with NPCs to solve simple quests, such as helping a thief to unlock a sealed door.

NPC Follower Mechanic: Convince the Thief to help you, and he will follow you on your journey, with animations matching your movements.

Side-Scrolling Action: In the platforming levels, you have full control over your character's movement and the ability to jump.

Health & Collectibles: Manage your health as you navigate dangerous traps and collect coins to complete the platforming stages.

Dynamic Bounded Camera: A smart camera smoothly follows the player while always staying within the boundaries of the level.

Full Menu & Pause System: The game includes a main menu, in-game menus, and a pause function for the exploration scenes.

📖 Gameplay Overview
The adventure unfolds across different interconnected scenes:

Explore the World: You begin in a top-down scene like SceneVille. You control Boo using 4-directional movement to explore the map.

Talk to Characters: You will encounter characters like the Sorcerer and the Thief. By entering their area, you can initiate conversations managed by the dialogue system.

Solve Quests: Progress by completing tasks. For example, interacting with the Thief can set a voleur_taken flag, which allows the Thief to follow you and lets you open a locked door.

Collect Items: Search the exploration maps to find and collect gems.

Unlock New Levels: Once you have collected at least 3 gems, you can access the entrance to the side-scrolling combat level.

Conquer the Platformer: In the combat level, the gameplay shifts. You must navigate the level, avoid traps, collect 3 coins, and manage your health to win.

🕹️ Controls

| Action            | Key                        | Gameplay Mode            |
| ----------------- | -------------------------- | ------------------------ |
| **Movement** | `Arrow Keys` (Up/Down/Left/Right) | Top-Down Exploration |
| **Movement** | `Left / Right Arrow Keys` | Side-Scrolling Platforming |
| **Jump** | `ui_accept` (Space/Enter)  | Side-Scrolling Platforming |
| **Advance Text** | `text` (Custom Action) | Dialogue |
| **Pause Game** | `ui_cancel` (Escape) | Top-Down Exploration |



Exporter vers Sheets
🚀 Getting Started
To run this project on your local machine, you'll need to have the Godot Engine installed.

Prerequisites
Godot Engine (Version 4.x recommended). You can download it from the official Godot website.

Installation & Setup
Clone the repository to your local machine.

Open the Godot Engine project manager.

Click the "Import" button.

Navigate to the cloned project folder and select the project.godot file.

Once imported, open the project and run the main scene (likely Menu1.tscn or SceneVille.tscn).

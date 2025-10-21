🎯 2D Shooter Project
A fast-paced, feature-rich 2D shooter built in Unity. Take control, blast through hordes of enemies, and survive as long as you can! This project showcases a complete game loop with polished systems and developer tools.

https://img.shields.io/badge/Unity-2022.1.24f1-black?style=for-the-badge&logo=unity
https://img.shields.io/badge/Platforms-WebGL%2520%257C%2520Windows-lightgrey?style=for-the-badge

🚀 Features
Intuitive Player Combat: Smooth controls with a dynamic shooting system.

Relentless Enemies: AI-driven enemies that spawn in waves for endless action.

Robust Game Systems: Health, damage, and scoring systems that form the core of the gameplay.

Polished User Interface: A clean UI to track your score and game state.

Developer Console: In-game debug console with custom commands for testing and tweaking.

High-Quality Text Rendering: Utilizes TextMesh Pro for crisp, shader-enhanced visuals.

Ready-to-Play Builds: Pre-built for WebGL (play in your browser) and Windows.

🛠️ Project Architecture
Here's a breakdown of the key scripts and systems that power the game:

System	Key Components	Description
🔥 Combat	ShootingController.cs, Projectile.cs	Handles player input, firing mechanics, and projectile physics.
👾 Enemies	Enemy.cs, EnemySpawner.cs	Controls enemy behavior, AI, and wave-based spawning logic.
❤️ Health & Damage	Health.cs, Damage.cs	Manages entity health, damage application, and destruction.
🎮 UI & Management	GameManager.cs, ScoreDisplay.cs, CursorChanger.cs	Oversees game state, score UI, and custom cursor.
⚙️ Developer Tools	DeveloperConsole.cs, ScreenshotUtility.cs, TimedObjectDestroyer.cs	Provides in-game debugging, commands, and utility functions.
🎮 Getting Started
Play Now!
WebGL Build: Click here to play in your browser! (Just open index.html)

For Developers
Clone the repository.

Open the project in Unity 2022.1.24f1 or a compatible version.

Explore the scenes located in the Assets/Scenes folder.

Use the Developer Console in-play mode for debugging (check the DeveloperConsole.cs for command list).

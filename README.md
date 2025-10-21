# 🎯 2D Shooter Project
[![Play on itch.io](https://img.shields.io/badge/Play%20On-itch.io-orange?style=for-the-badge&logo=itch.io)](https://humanhafezi.itch.io/2d-shooter)
A fast-paced, feature-rich 2D shooter built in Unity. Take control, blast through hordes of enemies, and survive as long as you can! This project showcases a complete game loop with polished systems, developer tools, and an engaging story-driven campaign.


![image alt](https://github.com/humansoul-ui/2D-Shooter/blob/main/image.png)
## 🚀 Features

- **Engaging Story Campaign:** Four unique levels tied together with an immersive narrative
- **Intuitive Player Combat:** Smooth controls with a dynamic shooting system
- **Advanced Enemy AI:** Smart enemies with directional shooting and scalable designs
- **Epic Boss Battles:** Challenging boss enemy with multiple attack patterns
- **Robust Game Systems:** Health, damage, and scoring systems that form the core of the gameplay
- **Polished User Interface:** Clean TextMesh Pro UI to track your score and game state
- **Developer Console:** In-game debug console with custom commands for testing and tweaking
- **High-Quality Text Rendering:** Utilizes TextMesh Pro for crisp, shader-enhanced visuals
- **Ready-to-Play Builds:** Pre-built for WebGL (play in your browser) and Windows

## 📖 Story & Level Design

Embark on an interstellar journey across 4 challenging levels:

1. **The Invasion Begins** - Defend against the initial wave of alien forces
2. **Asteroid Field Assault** - Navigate through dangerous asteroid fields while battling enemies
3. **Planetary Defense** - Protect inhabited planets with enhanced enemy spawners and planetary collisions
4. **Final Confrontation** - Face the ultimate boss in an epic showdown to save the galaxy

## 🛠️ Project Architecture

Here's a breakdown of the key scripts and systems that power the game:

| System | Key Components | Description |
| :--- | :--- | :--- |
| **🔥 Combat** | `ShootingController.cs`, `Projectile.cs` | Handles player input, firing mechanics, projectile physics with uniform scaling |
| **👾 Enemies** | `Enemy.cs`, `EnemySpawner.cs`, `BossEnemy.cs` | Advanced enemy AI with directional shooting, scalable sizes, and boss behaviors |
| **❤️ Health & Damage** | `Health.cs`, `Damage.cs` | Manages entity health, damage application, and destruction |
| **🎮 UI & Management** | `GameManager.cs`, `ScoreDisplay.cs`, `CursorChanger.cs` | Oversees game state, TextMesh Pro UI, and custom cursor |
| **⚙️ Developer Tools** | `DeveloperConsole.cs`, `ScreenshotUtility.cs`, `TimedObjectDestroyer.cs` | Provides in-game debugging, commands, and utility functions |
| **🌌 Level Design** | Multiple Scene files, Planetary colliders | Story-driven levels with environmental interactions |

## 🎮 Getting Started

### Play Now!
- **WebGL Build:** [Play on itch.io](https://humanhafezi.itch.io/2d-shooter)

### For Developers

1. **Clone the repository.**
2. **Open the project** in Unity 2022.1.24f1 or a compatible version.
3. **Explore the scenes** located in the `Assets/Scenes` folder.
4. **Use the Developer Console** in-play mode for debugging (check the `DeveloperConsole.cs` for command list).

## 🔧 Recent Updates & Enhancements

### 🎯 Enemy System Improvements
- **Directional Shooting:** Enemies can now save and use custom shooting directions
- **Scalable Enemies:** Complete compatibility with various enemy sizes and scales
- **Fixed Straight Shooter Bug:** Resolved issue with enemies always shooting downward
- **Enhanced Projectile System:** Added "Projectile Uniform Scale" for customizable bullet sizes

### 🦾 Boss Enemy & Final Mission
- **Smart Targeting:** Boss always faces and tracks player movement
- **Dual Attack Modes:** 
  - Two green projectiles that accurately target player position
  - One projectile that fires randomly into space for area denial
- **Unique Identity:** New skull icon and visual design
- **Epic Finale:** Special boss encounter in the last mission

### 🎨 UI & Visual Upgrades
- **TextMesh Pro Integration:** All menu text upgraded to high-quality TextMesh Pro
- **Professional Menus:** Enhanced main menu with clear instructions and story context
- **Consistent Typography:** Unified text rendering across all UI elements

### 🌍 Level Design Enhancements
- **Story Integration:** Added narrative context to all 4 levels
- **Environmental Interactions:** Added colliders to planets in Level 3 for realistic physics
- **Strategic Spawners:** Enhanced enemy spawner logic for Level 3 with planetary considerations
- **Progressive Difficulty:** Each level introduces new challenges and enemy types

### 🎮 Gameplay Polish
- **Expanded Instructions:** Comprehensive main menu tutorial and controls guide
- **Balanced Combat:** Refined enemy behaviors and projectile systems
- **Immersive Experience:** Story elements woven seamlessly into gameplay

---

**Ready for action? Jump into the story and test your skills across four challenging levels!**

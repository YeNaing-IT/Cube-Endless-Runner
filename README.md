# 🟦 Cube Endless Runner

**Cube Endless Runner** is a 3D endless runner game developed with **Unity and C#** for Androids.

The player controls a cube moving through an endless course filled with obstacles. The objective is to dodge obstacles, survive for as long as possible, and achieve the highest score.

The game focuses on simple controls, fast reactions, collision detection, and progressively challenging endless-runner gameplay.

## 🎮 Gameplay

The cube continuously travels through the level while obstacles appear along its path.

The player must move the cube and react quickly to avoid collisions.

### Objective

- Control the cube
- Dodge incoming obstacles
- Stay on the track
- Survive for as long as possible
- Increase your score
- Try to beat your previous run

## ✨ Features

- 🟦 Cube-based player
- 🏃 Endless runner gameplay
- 🧱 Obstacle avoidance
- 💥 Collision detection
- 🎯 Score tracking
- 🔄 Game restart system
- 🎮 Simple player controls
- ⚙️ Unity physics

## 🛠️ Built With

- **Unity**
- **C#**
- **Unity 3D**
- **Unity Physics**
- **Rigidbody**
- **Colliders**
- **Unity UI**

## 🎮 Controls

| Action | Control |
|---|---|
| Move Left | `Left-click` |

## 🧠 Unity Concepts Demonstrated

This project demonstrates several fundamental Unity game-development concepts:

- 3D player movement
- Rigidbody physics
- Collision detection
- Game state management
- Score tracking
- Scene management
- C# scripting
- Endless-runner game mechanics

## 🏃 Endless Runner System

Unlike a traditional level-based game, an endless runner is designed to continue until the player fails.

The core loop revolves around:

```text
Movement
   ↓
Obstacle Detection
   ↓
Dodge
   ↓
Continue Running
   ↓
Increase Score
   ↓
Repeat
```

This creates a simple gameplay loop where the difficulty comes from maintaining concentration and reacting quickly.

## 💥 Collision System

Obstacles use Unity colliders to detect contact with the player.

When the cube collides with an obstacle, the game can transition from the active gameplay state to the **Game Over** state.

```text
Player
   +
Obstacle
   ↓
Collision Detected
   ↓
Stop Run
   ↓
Game Over
```

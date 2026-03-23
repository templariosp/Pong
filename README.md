# 🏓 Pong (MonoGame)

A simple **Pong-style game** developed in **C# using MonoGame/XNA**.  
This project recreates the classic arcade gameplay where two players control paddles and try to score by sending the ball past the opponent.

Built as a learning project to explore **game development with MonoGame**, including input handling, collision detection, and basic game state management.

---

## 🎮 Gameplay

The game follows the traditional Pong mechanics:

- Two paddles (left and right)
- A bouncing ball
- Players must prevent the ball from passing their paddle
- When a player scores, a **GOAL screen** appears
- Press **SPACE** to continue the match

---

## 📸 Screenshots

### Gameplay

![Gameplay](screenshots/gameplay.png)

### Goal Screen

![Goal Screen](screenshots/goal.png)

---

## ⚙️ Features

- Classic Pong gameplay
- Paddle movement controls
- Ball physics and collision detection
- Goal detection system
- Game state transition (Play → Goal Screen)
- Continue gameplay with **Spacebar**
- Built using **MonoGame Framework**
- Clean and minimal project structure

---

## 🧱 Technologies Used

- **C#**
- **MonoGame Framework**
- **.NET**
- **Visual Studio**

MonoGame is an open-source implementation of Microsoft's **XNA Framework**, widely used for indie and retro-style game development.

---

## 📂 Project Structure


Pong/
│
├── Pong.sln
├── Pong/
│ ├── Game1.cs
│ ├── Program.cs
│ ├── Content/
│ └── Assets


Main responsibilities:

| File | Description |
|-----|-------------|
| `Program.cs` | Application entry point |
| `Game1.cs` | Main game loop (Update & Draw) |
| `Content/` | Game assets and resources |

---

## 🎮 Controls

| Key | Action |
|----|-------|
| W / S | Move left paddle |
| Up / Down Arrow | Move right paddle |
| Space | Continue after goal |

---

## ▶️ Running the Project

### Requirements

- Visual Studio 2022 or newer
- .NET SDK
- MonoGame Framework installed

### Steps

1. Clone the repository:

```bash
git clone https://github.com/templariosp/Pong.git

Open the solution:

Pong.sln

Build and run the project.

📚 Learning Goals

This project demonstrates:

Game loop architecture

Input handling

Collision detection

Basic game state management

Rendering with SpriteBatch

🚀 Future Improvements

Possible improvements for the project:

Score system

Sound effects

Start menu

AI opponent

Increasing ball speed over time

Game reset system

📜 License

This project is open source and available under the MIT License.

👨‍💻 Author

Developed by Thiago Simões

Software Architect & Indie Game Developer

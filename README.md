# 🌱 Conway's Game of Life — Raylib Simulation (C++)

This project is a graphical simulation of **Conway's Game of Life**, implemented in **C++** using the **Raylib** graphics library. It features real-time interactivity, customizable grids, and a toroidal (wrap-around) world—designed with Object-Oriented Programming principles.

---

## 🧠 About the Game of Life

Conway's Game of Life is a zero-player game where cells on a grid live, die, or multiply based on a set of simple rules. Despite the simplicity, it produces surprisingly complex behaviors and is a classic example of cellular automata.

---

## 🎮 Features

- **Real-time Simulation**: Watch generations evolve in real time.
- **Interactive Controls**:
  - **Speed Adjustment**: Speed up or slow down the simulation.
  - **Random Generation**: Instantly populate the grid with random live cells.
  - **Mouse Editing**: Manually toggle individual cells on or off to create custom patterns.
- **Toroidal Grid**: The grid wraps around the edges, giving the illusion of an infinite world.
- **Object-Oriented Design**: Clean and modular C++ code structure.

---

## 🧰 Technologies Used

- **Language**: C++
- **Graphics Library**: [Raylib](https://www.raylib.com/)
- **Build System**: g++ (can be configured with `task.json` or `CMake`)

---

## 🚀 Getting Started

### Prerequisites

- Install [Raylib](https://github.com/raysan5/raylib/wiki/Working-on-Windows)
- A C++ compiler (e.g., `g++`)
- Git (optional, for cloning the repository)

### Clone and Build

```bash
git clone https://github.com/the-jola-amodu/Conway-Game-of-Life-Simulation.git
cd Conway-Game-of-Life-Simulation
g++ *.cpp -o gameoflife -lraylib -lopengl32 -lgdi32 -lwinmm
./gameoflife

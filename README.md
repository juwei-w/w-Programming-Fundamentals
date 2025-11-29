# Alien vs. Zombie

![Game Screenshot](./Starter-Kit-master%20(Part%202)/Program.png)

A C++ console-based turn-based strategy game where players control an alien navigating a 2D grid to defeat zombies using strategic movement and game objects. Developed in 2023 as part of a Programming Fundamentals course assignment.

---

## 🎮 Overview

This repository showcases two development iterations demonstrating progressive feature enhancement and programming proficiency in C++. The game combines strategy, resource management, and tactical combat mechanics.

**Development Team:**
- Wong Ju Wei (Lead Developer)
- Yap Rui Ern (Developer)
- Lim Jia Hen (Developer)

---

## 📁 Repository Structure

```
w-Programming-Fundamentals/
├── Starter-Kit-master (Part 1)/
│   ├── pf/                    # Programming fundamentals resources
│   ├── main.cpp               # Main game implementation (Part 1)
│   ├── demo.cpp               # Demo/test code
│   ├── README.md              # Part 1 documentation
│   ├── PART1.md               # Part 1 progress log
│   ├── PART2.md               # Part 2 progress log
│   └── Program.png            # Game screenshot
│
└── Starter-Kit-master (Part 2)/
    ├── pf/                    # Programming fundamentals resources
    ├── main.cpp               # Enhanced game implementation (Part 2)
    ├── README.md              # Part 2 documentation
    ├── PART1.md               # Part 1 progress log
    ├── PART2.md               # Part 2 progress log
    └── Program.png            # Game screenshot
```

---

## 🎯 Game Features

### Part 1: Foundation
- Customizable game board (adjustable rows/columns)
- Random zombie placement
- Turn-based combat system
- **Game Objects:**
  - 🏥 Health Packs - Restore health
  - 🫘 Pods - Attack mechanisms
  - 🪨 Rocks - Obstacles
  - ⬆️ Arrows - Change movement direction

### Part 2: Enhanced Edition
All Part 1 features plus:
- **Difficulty levels** for varied challenge
- **Enhanced mechanics:** Health packs (+20 HP), Arrows (+20 attack)
- **Intelligent pod targeting** (attacks nearest zombie)
- **Advanced interactions:** Rocks block movement and drop objects
- **New obstacle:** 🌟 Spikes (-10 HP to alien)
- **Save/Load system** for persistent gameplay
- **Expanded command set**

---

## 🔧 Getting Started

### Prerequisites
- C++ Compiler (GCC, MinGW, MSVC, or similar)
- C++11 or later

### Compilation
```bash
# Using IDE (VS Code)
Open main.cpp → Press F5 or click debug button

# Command Line
g++ main.cpp -o alien_zombie.exe

# With multiple source files
g++ main.cpp pf/code.cpp -o game.exe
```

---

### Game Commands
| Command | Action |
|---------|--------|
| `up`, `down`, `left`, `right` | Move alien |
| `arrow` | Change arrow direction |
| `save`, `load` | Save/load game (Part 2) |
| `help` | Display commands |
| `quit` | Exit game |

---

### How to Play
1. Run the compiled executable
2. Customize settings (board size, zombie count, difficulty)
3. Navigate using directional commands
4. Collect health packs and utilize game objects strategically
5. Defeat all zombies to win!

---

## 📹 Demo Videos & Documentation
- [Part 1 Video Demo](https://www.youtube.com/watch?v=pO5W0PhPbMc)
- [Part 2 Video Demo](https://youtu.be/DpwxYc-8l2A)
- [Part 1 Progress Log](./Starter-Kit-master%20(Part%201)/PART1.md)
- [Part 2 Progress Log](./Starter-Kit-master%20(Part%202)/PART2.md)

---

## 🎓 Educational Objectives

This project was developed to demonstrate proficiency in core programming concepts:

### Programming Concepts Demonstrated
- **Object-Oriented Programming (OOP)** in C++
- **Algorithm Design** for game mechanics and logic
- **Data Structure Implementation** for game board management
- **User Input Handling** and validation
- **Random Generation Algorithms** for dynamic gameplay
- **File I/O Operations** for save/load functionality (Part 2)
- **Memory Management** in C++
- **Code Organization** and modular programming

### Technical Architecture

#### Core Components
1. **Game Board System**
   - 2D array/vector implementation
   - Dynamic sizing based on user configuration
   - Cell state management (empty, occupied, object type)

2. **Entity Management**
   - Alien character with health and position tracking
   - Zombie entities with individual states
   - Object placement and interaction system

3. **Command Processing**
   - Input parsing and validation
   - Command execution engine
   - Help system implementation

4. **Random Generation**
   - Pseudo-random number generation for zombie placement
   - Random object distribution across the board

5. **Save/Load System** (Part 2)
   
---

## 💻 Technical Implementation

### Core Programming Concepts
- **Object-Oriented Programming (OOP)** - Classes for entities and game objects
- **Data Structures** - 2D arrays/vectors for board representation
- **Algorithm Design** - Pathfinding, random generation, nearest neighbor search
- **File I/O Operations** - Save/load game state (Part 2)
- **Input Validation** - Robust error handling and user input processing
- **Memory Management** - Proper resource allocation in C++

### System Architecture
1. **Game Board System** - Dynamic 2D grid with cell state management
2. **Entity Management** - Alien/zombie tracking with health and position
3. **Command Processing** - Input parsing and execution engine
4. **Random Generation** - Zombie placement and object distribution
5. **Combat Resolution** - Damage calculation and victory conditions
6. **Save/Load System** - Game state serialization (Part 2)

---

### Learning Outcomes
This project demonstrates:
- Software design and implementation
- Complex game logic and algorithms
- Version control and team collaboration
- Iterative development practices
- Code organization and documentation
- Testing and debugging methodologies

---

## 🔗 Resources

- **Repository:** [github.com/juwei-w/w-Programming-Fundamentals](https://github.com/juwei-w/w-Programming-Fundamentals)
- **Issues:** [Report a bug](https://github.com/juwei-w/w-Programming-Fundamentals/issues)

---

*Programming Fundamentals Course Assignment • Degree Year 1 Sem 1 • Nov 2022 - March 2023*
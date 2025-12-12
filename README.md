# 🎮 Basic Pacman Game in C

A simple console-based Pacman game written in C using only basic programming concepts.

## 📝 Description

This is a beginner-friendly Pacman game implementation that demonstrates fundamental C programming concepts. The game runs in the terminal/console where players control Pacman to collect dots while avoiding a ghost enemy.

## ✨ Features

- Simple text-based graphics using ASCII characters
- Player-controlled Pacman character
- AI-controlled ghost that chases the player
- Score tracking system
- Walls and obstacles
- Win/lose conditions

## 🎯 Game Objective

- Collect all dots (.) on the map to win
- Avoid the ghost (G) - if it catches you, game over!
- Each dot collected gives you 10 points

## 🕹️ Controls

- `w` or `W` - Move Up
- `s` or `S` - Move Down
- `a` or `A` - Move Left
- `d` or `D` - Move Right
- `x` or `X` - Exit Game

## 🛠️ Technical Details

**Programming Concepts Used:**
- Only `if` statements and `while` loops
- 2D arrays for map representation
- Basic input/output (scanf/printf)
- Integer and character variables
- Simple game loop logic

**No advanced features:**
- No functions (everything in main)
- No for loops
- No switch statements
- No external libraries beyond stdio.h

## 💻 How to Compile and Run

### On Linux/Mac:
```bash
gcc pacman.c -o pacman
./pacman
```

### On Windows:
```bash
gcc pacman.c -o pacman.exe
pacman.exe
```

## 📋 Requirements

- GCC compiler (or any C compiler)
- Terminal/Console window
- Basic C knowledge

## 🎓 Learning Outcomes

This project is perfect for beginners learning C programming. You'll understand:
- How to use nested while loops
- Working with 2D arrays
- Basic game logic implementation
- Conditional statements (if-else)
- User input handling
- Simple AI for enemy movement

## 🎨 Game Map Legend

- `#` - Walls (cannot pass through)
- `.` - Dots (collect these for points)
- `C` - Pacman (you control this)
- `G` - Ghost (avoid this!)
- ` ` - Empty space (dot already collected)

## 🚀 Future Improvements

Possible enhancements for learning:
- Add multiple ghosts
- Add power-ups
- Implement lives system
- Create larger maps
- Add difficulty levels
- Implement high score saving

## 📄 License

Free to use for educational purposes.

## 👨‍💻 Author

Created as a learning project for basic C programming.

---


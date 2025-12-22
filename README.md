<div align="center">

# ⭕ Tic-Tac-Toe in C++

### A classic two-player strategy game with colorful console graphics

[![Play Now](https://img.shields.io/badge/🎮_Play-Now-ff4444?style=for-the-badge&logo=cplusplus&logoColor=white)](https://github.com/Mikky-mlh/Tic-Tac-Toe-in-CPP/raw/main/TTT.exe)
[![License](https://img.shields.io/badge/📜_License-MIT-0080ff?style=for-the-badge)](./LICENSE)
[![C++](https://img.shields.io/badge/C++-11+-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org/)

![Game Status](https://img.shields.io/badge/Status-Playable-success?style=flat-square)
![Last Updated](https://img.shields.io/badge/Updated-December_2025-orange?style=flat-square)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [How to Play](#-how-to-play)
- [What I Learned](#-what-i-learned)
- [Project Structure](#-project-structure)
- [Future Improvements](#-future-improvements)
- [Connect](#-connect)

---

## 🎯 About

Tic-Tac-Toe is a classic two-player game where players take turns marking spaces in a 3×3 grid. The player who succeeds in placing three marks in a horizontal, vertical, or diagonal row wins. This C++ implementation features colorful console graphics and plays against an AI opponent.

---

## ✨ Features

- 🎨 **Colorful Console UI** - Green for player, Red for computer, Cyan accents
- 🤖 **AI Opponent** - Play against the computer
- 🔄 **Quick Restart** - Play multiple rounds
- 🏆 **Smart Win Detection** - Checks all winning patterns
- 🤝 **Draw Handling** - Detects tie games
- 🎯 **Number-Based Input** - Simple 1-9 position selection

---

## 🛠 Tech Stack

<div align="center">

![C++](https://img.shields.io/badge/C++_11+-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

</div>

---

## 📦 Installation

### 🚀 Quick Start (Windows)

**Just want to play? Download and run the executable:**

1. Download `TicTacToe.exe` from the repository
2. Double-click `TicTacToe.exe` to run
3. If Windows shows a security warning, click **"More info"** → **"Run anyway"**

### 🔧 Compile from Source

```bash
# Clone the repository
git clone https://github.com/Mikky-mlh/Tic-Tac-Toe-in-CPP.git

# Navigate to directory
cd Tic-Tac-Toe-in-CPP

# Compile the game
g++ TTT.cpp -o TicTacToe.exe

# Run the game
TicTacToe.exe
```

---

## 🎮 How to Play

1. **Start Game** - The board displays with positions numbered 1-9
2. **Make Moves** - Enter a number (1-9) to place your X (Green)
3. **Computer Turn** - AI automatically places O (Red)
4. **Win/Draw** - Connect 3 in a row or fill the board
5. **Play Again** - Press Y to restart or N to quit

### Controls

| Action | Control |
|:-------|:--------|
| Place X | **Type 1-9** → **Enter** |
| Play Again | **Y** |
| Quit | **N** |

### Board Layout

```
 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9
```

---

## 📚 What I Learned

My first C++ game project, teaching me:
- **Windows Console API** - Using `windows.h` for color manipulation with `SetConsoleTextAttribute()`
- **Console Graphics** - Drawing game boards with ASCII characters and colors
- **Game Logic Patterns** - Win condition checking across 8 possible lines (3 rows, 3 columns, 2 diagonals)
- **Random Number Generation** - Using `rand()` and `srand(time(0))` for AI opponent
- **Input Validation** - Ensuring moves are valid before accepting them
- **Game Loop Structure** - Managing turns, checking win/draw conditions, restart functionality

**Platform Note:** This uses Windows-specific APIs (`windows.h`), making it Windows-only. Future versions could use cross-platform libraries like ncurses (Linux/Mac terminal graphics library) for portability.

---

## 📂 Project Structure

```
Tic-Tac-Toe-in-CPP/
│
├── 📄 TTT.cpp              # Main game logic and console rendering
├── 🎮 TicTacToe.exe        # Windows executable (ready to play)
├── 📖 README.md            # Project documentation
└── 📜 LICENSE              # MIT License
```

### Key Functions

- `drawBoard()` - Render colorful 3×3 grid
- `playerMove()` - Handle player input
- `computerMove()` - Random AI move generation
- `checkWinner()` - Validate win conditions
- `checkTie()` - Detect draw games
- `setColor()` - Console color management

---

## 🔮 Future Improvements

Planned enhancements:
- 🖱️ **Mouse Click Support** - Exploring Win32 API mouse events or transitioning to SDL2/SFML (game development libraries that handle graphics and input)
- 🧠 **Minimax AI** - Unbeatable AI using minimax algorithm (AI decision-making algorithm that evaluates all possible moves)
- 🎮 **Two-Player Mode** - Human vs Human option
- 💾 **Score Tracking** - Persistent win/loss statistics
- 🌈 **Cross-Platform** - Port to ncurses for Linux/macOS support

> **Note:** Current implementation uses Windows-specific console APIs. Cross-platform version would require rewrite using portable libraries.

---

## 🤝 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mikky-mlh)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yuvraj-sarathe)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Mikky_mlh/)

### 💬 Contributions Welcome!

Found a bug or have ideas? Open an issue or submit a pull request!

</div>

---

<div align="center">

### ⭕ "Three in a row, ready to go!"

**Made with ❤️ by [Yuvraj Sarathe](https://github.com/Mikky-mlh)**

⭐ **Star this repo if you enjoyed the game!**

*Last Updated: December 22, 2025*

</div>

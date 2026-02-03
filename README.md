# 🎮 Tic-Tac-Toe (Python CLI Game)

A simple **command-line Tic-Tac-Toe game** written in Python for two players.  
Players take turns entering positions (0–8) to place their mark (`X` or `O`).  
The game checks for winners and detects draw conditions.

---

## 📌 Features

- Two-player mode (`X` vs `O`)
- Board displayed in terminal
- Input validation
- Automatic winner detection
- Draw (“Cat’s game”) detection
- Simple and beginner-friendly code

---

## 🧠 How It Works

- The board is stored in a list of 9 elements.
- Players alternate turns.
- Win conditions are predefined for:
  - Rows
  - Columns
  - Diagonals
- After every move, the program checks:
  - If a player won
  - If the board is full

---

## ▶️ How to Run

### 1️⃣ Prerequisites
Make sure Python is installed:

```bash
python --version

# Football_Chess

# ⚽ Football Chess

A fun and strategic web app game that blends football club/national team knowledge with a chess-inspired board game!

---

## 🎮 Game Overview

- **Board**: A 8x8 grid:
  - **Top row** and **left column**: Football club and national team crests.
  - **7x7 grid**: Where players make their moves.

- **Objective**: Players take turns guessing **players who have played for the club (column) and national team or club (row)** at the intersection.  
- **Win Condition**:  
  - **Connect 4-style**: First player to fully conquer a row, column, or diagonal wins!  
  - If no full line is conquerable, the player with **most boxes occupied** wins.

---

## 🏁 Game Rules

1. **Player 1 (Blue)** and **Player 2 (Green)** alternate turns.
2. Each turn:
   - Select a grid cell (intersection of row and column crest).
   - Confirm with:
     - ✅ **Green Tick**: Correct guess, cell is occupied.
     - ❌ **Red Cross**: Wrong guess, cell remains empty and turn passes to opponent.
     - ➖ **Gray Dash**: Cell is known to have no valid player (neutral).
3. Each player has **30 minutes** total to play (countdown timer).
4. After confirming:
   - Cell is locked and colored with the player’s color.
   - Turn passes to the opponent.

---

## 🚀 Features

- Responsive design (mobile & desktop friendly).
- Player headers with:
  - Occupied cell count.
  - Remaining time.
  - Active turn highlight.
- “Reset” button to start a new game at any time.
- Victory animation overlay when a player wins!

---


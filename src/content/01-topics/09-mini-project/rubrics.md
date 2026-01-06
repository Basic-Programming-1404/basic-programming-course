# 🎮 Othello C++ Mini Project — Grading Rubric

**Total Points: 800**

---

## 1. Correct Board Display (Rendering) — **80 points**
- Correct board size (e.g., 8×8)
- Clear display of cells and pieces
- Proper alignment and spacing
- Board updates correctly after each move

---

## 2. Input Handling, Screen Control, and WASD Movement — **80 points**

- Proper use of `getch` (no Enter required)
- Correct screen clearing at appropriate times
- Smooth cursor movement using `W`, `A`, `S`, `D`
- Cursor stays within board boundaries
- Correct cell selection mechanism

---

## 3. Core Game Logic and End-Game Conditions — **200 points**

- Correct detection of valid moves
- Proper flipping of pieces in **all directions**
- Rejection of illegal moves
- Correct turn switching
- Accurate detection of game-ending conditions:
    - Full board
    - No valid moves for both players
- Correct score calculation and winner declaration



---

## 4. Single-Player Mode and Bot Functionality — **100 points**
- Ability to play against a bot
- Bot always makes valid moves
- Bot does not crash or freeze the game
- Bot logic is consistent and reasonable (even if simple)

---

## 5. Menu System — **60 points**
- Clear and functional main menu
- Correct navigation between options
- Proper handling of user selections

---

## 6. Leaderboard Saving and Display — **70 points**
- Correct use of file I/O
- Persistent storage of player data
- Clean and readable leaderboard display
- Data is not corrupted between runs
    

---

## 7. User Interface Quality (UI/UX) — **50 points**
- Readable text-based interface
- Proper spacing and alignment
- Consistent visual style
- Overall pleasant user experience
    

---

## 8. Code Cleanliness, Structure, and Modularity — **90 points**
- Well-structured code with clear functions
- Meaningful naming conventions
- Minimal duplication
- Logical separation of concerns
- Readable and maintainable code
    

---

## 9. Code Understanding and Mastery — 70 points**
- Student can clearly explain their implementation
- Demonstrates strong understanding of logic
- Can modify or extend the code if asked
- Code is not blindly copied or auto-generated
    

---

## ✅ Points Summary

| Category                    | Points  |
| --------------------------- | ------- |
| Board Display               | 80      |
| Input & Movement            | 80      |
| Game Logic & End Conditions | 200     |
| Single-Player & Bot         | 100     |
| Menu System                 | 60      |
| Leaderboard                 | 70      |
| UI / UX                     | 50      |
| Code Structure              | 90      |
| Code Mastery                | 70      |
| **Total**                   | **800** |





# Bonus Features — **Up to 200 Points**

## 1. Save & Load Game State — **20 points**
- Ability to **save the game during gameplay** (e.g., via a specific key or on exit)
- Complete game state is saved:
    - Board state
    - Current player’s turn
    - Game mode (single/multiplayer, board size, etc.)
- Game can be **loaded later** via a “Load Game” menu option
- Loaded game resumes correctly from the saved state

---
## 2. Advanced Bot Algorithms (e.g., Minimax) — Up to **80 points**
- Implementation of an advanced decision-making algorithm such as:
    - Minimax
    - Minimax with depth limit
    - Alpha–Beta pruning
- Bot evaluates game states instead of choosing random or first-available moves
- Algorithm is stable and does not significantly degrade performance

---
## 3. Visual Enhancement with ANSI Colors — **20 points**
- Use of ANSI color codes for:
    - Black and white pieces
    - Board highlights
    - Menus or messages
- Colors improve clarity and aesthetics
- UI remains readable and consistent across the game

---

## 4. Configurable Board Size — **10 points**
- User can select board size at the start of the game
- Board size is **even and valid** (e.g., 6×6, 8×8, 10×10)
- All game logic (moves, flips, end-game detection) adapts correctly to the chosen size

---

## 5. Display of Valid Moves (Hints) — **10 points**

- Valid moves for the current player are visually indicated on the board
- Uses a distinct marker (e.g., dim `*` or highlighted cell)
- Hints update correctly when the turn changes
- Hint display does not interfere with gameplay

---

## 6. Game Replay Feature — **20 points**

- All moves are recorded during gameplay
- After the game ends, user can replay the game from start to finish
- Replay shows moves step-by-step in correct order
- Controls for replay progression (automatic or manual) are reasonable

---

## 8. Creative Features & Enhancements — **Up to 40 points**

- Any original or creative idea that meaningfully improves the game, such as:
    - Difficulty levels
    - Undo move
    - Animations or delays
    - Better menus or transitions
- Feature must be functional and integrated into the game
    



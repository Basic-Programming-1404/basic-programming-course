# 🎮 Breakout — Final Project Grading Rubric

**Total Points:** **3000**

---

## 1. Correct Board Display (Rendering) — **400 pts**
- Proper alignment and spacing of the board, paddle, ball, and bricks
- Board dimensions remain consistent throughout the game
- Visual elements (walls, bricks, paddle, ball) are clearly distinguishable
- Screen updates correctly in real time (no visual artifacts or leftover characters)
- Rendering logic is efficient and does not cause flickering or lag
- HUD contains the elements mentioned in the document: current score, remaining "hearts", number of remaining breaks
**Partial Credit:**
- Minor alignment issues or occasional rendering glitches

---

## 2. Input Handling, Screen Control, and Movement — **200 pts**
- Proper use of `getch()` or equivalent (no need to press Enter)
- Correct and minimal screen clearing (no unnecessary full redraws)
- Smooth paddle or cursor movement using `W`, `A`, `S`, `D` (or specified controls)
- Input is responsive and does not feel delayed
- Player movement stays within board boundaries
- Correct handling of invalid or irrelevant key presses

**Penalty Examples:**
- Blocking input (`cin`) during gameplay
- Paddle or cursor leaving the board

---

## 3. Core Game Logic and End-Game Conditions — **500 pts**
- Correct ball movement and direction updates
- Accurate collision detection:
    - Ball with walls
    - Ball with paddle
    - Ball with bricks
- Bricks are removed correctly upon collision
- Score updates correctly based on gameplay events
- Game ends correctly when:
    - Player wins (all bricks destroyed)
    - Player loses (ball falls below paddle / lives reach zero)
- Proper handling of multiple lives 

**Critical Errors (Major Deduction):**
- Ball passes through bricks
- Game never ends or ends incorrectly

---

## 4. AI Usage Report — **300 pts**
- A complete report written on how AI was used


---

## 5. Menu System (Main Menu & Pause Menu)— **300 pts**

- Clear and functional main menu
- Options such as:
    - Start Game
    - Help
    - Game History - Leaderboard
    - Exit
- Correct navigation between menu options
- Menu input handling is robust (no crashes on invalid input)
- Smooth transition between menu and gameplay
- **Pause menu** implemented correctly 

---

## 6. Leaderboard Saving and Display — **300 pts**
- Correct use of file I/O (`fstream`)
- Player scores are saved persistently across runs
- Leaderboard loads correctly on program start
- Clean, readable leaderboard display (sorted if required)
- Data is not corrupted or duplicated between runs
- Graceful handling of missing or empty leaderboard files

**Penalty Examples:**
- Overwriting previous data incorrectly
- Crashing when file does not exist

---

## 7. User Interface Quality (UI / UX) — **300 pts**
- Readable text-based interface (clear fonts, symbols, spacing)
- Consistent visual style throughout the game
- Clear feedback to the user (score, lives, game over message)
- Instructions or controls are visible or explained
- Overall pleasant and understandable user experience

---

## 8. Code Cleanliness, Structure, and Modularity — **400 pts**
- Well-structured code with logical organization
- Use of functions to separate responsibilities (rendering, input, logic, file I/O)
- Meaningful variable and function names
- Minimal code duplication
- Proper use of constants instead of magic numbers
- Reasonable file structure (if multiple files are used)
- Code follows basic C++ best practices
**Major Deductions:**
- Entire program written in `main()`
- Excessive global variables without justification

---

## 9. Code Understanding and Mastery — **300 pts**
- Student can clearly explain how their game works
- Demonstrates strong understanding of:
    - Game loop
    - Input handling
    - Collision logic
- Can modify or extend the code when asked (small change)
- Code is not blindly copied or fully auto-generated
- Student answers questions confidently and logically

**Zero or Near-Zero Credit If:**
- Student cannot explain their own code
- Logic is memorized but not understood

---
# Bonus Features — **Up to 1500 Points**

**Maximum Bonus Points:** **1500**  
_(Bonus points are awarded only after core project requirements are satisfied.)_

---

## 10. Dynamic Difficulty Adjustment — **400 pts**
The game dynamically increases difficulty as the player progresses.
Possible implementations include (one or more):
- Ball speed increases after breaking a certain number of bricks
- Paddle size decreases in later stages
- Brick density or number of rows increases over time
- Difficulty progression feels gradual and fair
**Evaluation Criteria:**
- Difficulty scaling is intentional and not arbitrary
- Game remains playable and balanced
- Logic is stable and does not break core mechanics

**Partial Credit:**
- Difficulty increases but is abrupt or poorly balanced

---

## 11. Multi-Level Gameplay — **400 pts**

- Game includes **multiple distinct levels**
- Each level has a different brick layout or configuration
- Smooth transition between levels (no program restart)
- Player state is preserved between levels:
    - Score
    - Remaining lives
- Clear indication of level progression (message or visual cue)

**Major Deduction:**
- Levels reset score or lives incorrectly

---

## 12. Power-Ups and Special Mechanics — **400 pts**

Optional power-ups may be implemented, such as:
- Multiple balls active simultaneously (recommended)
- Temporary paddle size increase
- Ball speed reduction
- Temporary score multiplier

**Evaluation Criteria:**
- Power-ups activate correctly (random or rule-based)
- Effects are temporary and handled safely
- Multiple power-ups do not crash or destabilize the game
- Clear feedback is shown when a power-up is active

**Partial Credit:**
- Power-ups exist but lack proper timing or feedback

---

## 13. High Score Tracking — **100 pts**

- Highest score is stored in a text file
- High score persists between game runs
- High score is displayed clearly in the game or menu
- Stored value updates correctly when beaten
- File I/O errors are handled gracefully

---

## 14. Additional & Creative Features — **200 pts**

This section rewards **original, well-implemented ideas** not explicitly listed elsewhere.
Examples include (but are not limited to):
- Different brick types (unbreakable, multi-hit, bonus bricks)
- Visual effects or animations in the terminal
- Sound effects (if platform allows)
- Pause / resume functionality
- Cheat/debug mode for testing
- Customizable controls
- Replay or demo mode

**Evaluation Criteria:**
- Feature is functional and stable
- Adds meaningful value to gameplay
- Is well-integrated into the existing codebase
- Student can clearly explain the idea and its implementation

---


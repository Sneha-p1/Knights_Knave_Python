# Knight & Knave: The Logic Quest — Python Edition

A desktop version of the fantasy-themed logic puzzle game, made with **Python and Tkinter only**. It does not use HTML, CSS, JavaScript, Node.js, or any external Python packages.

## Files

- `game.py` — the complete game.
- `README.md` — setup and playing instructions.

## Features

- Intro screen and player name
- Easy, Medium, and Hard levels
- The original 9 puzzle titles, statements, hints, explanations, and intended answers
- Knight, Knave, and Spy role selection
- Answer checking, points, hint penalty, and player ranks
- Level unlocking after completing the previous level
- Achievements screen
- Sound toggle using the computer's built-in Tkinter bell
- Victory popup and fantasy-themed dark interface

## Requirements

- Python 3
- Tkinter (usually included with Python on Windows; on Ubuntu/Linux it may need to be installed separately)

No `pip install` packages are required.

## Run on Ubuntu/Linux

1. Extract the ZIP file.
2. Open a terminal in the extracted `Knights_Knave_Python` folder.
3. Check Python:

   ```bash
   python3 --version
   ```

4. If Tkinter is missing, install it:

   ```bash
   sudo apt update
   sudo apt install python3-tk
   ```

5. Run the game:

   ```bash
   python3 game.py
   ```

## Run in VS Code

1. Open the extracted folder in VS Code.
2. Open `game.py`.
3. Select **Run Python File** (or run `python3 game.py` in the terminal).

## How to Play

1. Click **PLAY GAME**.
2. Enter a player name.
3. Choose an unlocked level.
4. Read each character's statement.
5. Select Knight, Knave, or Spy for every character.
6. Click **CHECK LOGIC**.
7. Use **HINT** if you need help. Hints reduce the points earned for a correct answer.
8. Finish a level to unlock the next one and earn achievements.

## Role Rules

- **Knight:** Always tells the truth.
- **Knave:** Always lies.
- **Spy:** May tell the truth or lie.

## Important note

This is a Python desktop recreation of the browser game, not a line-for-line conversion. Browser-only effects such as the original canvas snow and Web Audio sound synthesis are replaced with Tkinter-compatible effects. The original 9 puzzle entries and intended answers are carried over. As in the original project, answers are checked against the puzzle's predefined intended answers rather than solving arbitrary logic statements dynamically.

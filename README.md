# AI-connect4
# Connect 4 Game

A Python implementation of the classic **Connect 4** game built with **Pygame**, featuring both **Player vs Player** and **Player vs AI** game modes.

## Features

* Two-player mode (Player vs Player)
* Single-player mode (Player vs AI)
* AI opponent using **Minimax Algorithm** 
* Score tracking system
* Interactive graphical user interface (GUI)
* Win detection (horizontal, vertical, diagonal)
* Draw detection
* Reset board after each round
* Main menu navigation

---

## Project Structure

```bash
Connect4/
│── main.py                 # Main menu and game launcher
│── board.py                # Board creation and game logic
│── play.py                 # Player vs Player mode
│── play_ai.py              # Player vs AI mode
│── MinMax_implementation.py # AI logic
│── button.py               # Button class for GUI
│── ASSET/                  # Images and assets
│── tests/                  # Unit tests
│── README.md               # Project documentation
```

---

## Requirements

Install dependencies:

```bash
pip install pygame numpy
```

---

## How to Run

Run the game:

```bash
python main.py
```

---

## How to Play

1. Launch the game.
2. Choose:

   * **Play** → Player vs Player
   * **Play AI** → Player vs Computer
3. Players take turns dropping pieces.
4. First player to connect 4 pieces wins the round.
5. Points are awarded:

   * Win = 10 points
   * Draw = 5 points each
6. First player to reach the maximum score wins.

---

## Game Rules

* Board size: **6 rows × 7 columns**
* Two piece colors:

  * Red (Player 1)
  * Yellow (Player 2 / AI)
* Pieces fall to the lowest available slot in the selected column.
* Win conditions:

  * Horizontal
  * Vertical
  * Diagonal

---

## AI Implementation

The AI uses:

* **Minimax Algorithm**

* Board evaluation scoring

This allows the AI to make strategic moves and block the player.

---

## Testing

Run unit tests:

```bash
python -m unittest
```

Tests include:

* Board creation
* Piece placement
* Row validation
* Win condition detection
* Board reset

---

## Technologies Used

* Python 3
* Pygame
* NumPy


---

## Future Improvements

* Difficulty levels for AI
* Better UI/UX
* Sound effects
* Online multiplayer
* Save game progress

---



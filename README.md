# AI-connect4
A Python implementation of the classic Connect 4 game built with Pygame, featuring both Player vs Player and Player vs AI game modes and with points.

Features
Two-player mode (Player vs Player)
Single-player mode (Player vs AI)
AI opponent using Minimax Algorithm with Alpha-Beta Pruning
Score tracking system
Interactive graphical user interface (GUI)
Win detection (horizontal, vertical, diagonal)
Draw detection
Reset board after each round
Main menu navigation
Project Structure
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
Requirements
Install dependencies:

pip install pygame numpy
How to Run
Run the game:

python main.py
How to Play
Launch the game.

Choose:

Play → Player vs Player
Play AI → Player vs Computer
Players take turns dropping pieces.

First player to connect 4 pieces wins the round.

Points are awarded:

Win = 10 points
Draw = 5 points each
First player to reach the maximum score wins.

Game Rules
Board size: 6 rows × 7 columns

Two piece colors:

Red (Player 1)
Yellow (Player 2 / AI)
Pieces fall to the lowest available slot in the selected column.

Win conditions:

Horizontal
Vertical
Diagonal
AI Implementation
The AI uses:

Minimax Algorithm
Alpha-Beta Pruning
Board evaluation scoring
This allows the AI to make strategic moves and block the player.

Testing
Run unit tests:

python -m unittest
Tests include:

Board creation
Piece placement
Row validation
Win condition detection
Board reset
Technologies Used
Python 3
Pygame
NumPy
Future Improvements
Difficulty levels for AI
Better UI/UX
Sound effects
Online multiplayer
Save game progress
License
This project is for educational purposes.

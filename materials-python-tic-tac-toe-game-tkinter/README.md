# Python Tic-Tac-Toe Game with Tkinter

A feature-rich implementation of the classic Tic-Tac-Toe game using Python and Tkinter. This project demonstrates how to build a graphical user interface (GUI) game with Python, implementing game logic, user interaction, and a clean architecture.

## Project Structure

```
materials-python-tic-tac-toe-game-tkinter/
├── README.md
├── source_code_final/
│   └── tic_tac_toe.py      # Complete implementation of the game
└── source_code_step_1-5/   # Development steps showing progressive implementation
    └── tic_tac_toe.py      # Implementation at each step
```

## Features

- 6x6 game board (customizable size)
- Two-player gameplay
- Colorful UI with X (blue) and O (green) players
- Win detection for rows, columns, and diagonals
- Game state management
- Interactive GUI with Tkinter
- Menu bar with "Play Again" and "Exit" options
- Clear game status display
- Winning combination highlight
- Tie game detection

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)
- No additional dependencies required

## Installation

No special installation is needed. Just ensure you have Python installed on your system with Tkinter support (version ≥ 8.6).

## How to Run

1. Navigate to the source_code_final directory:
   ```bash
   cd source_code_final
   ```

2. Run the game:
   ```bash
   python tic_tac_toe.py
   ```

## Game Implementation Details

The game is implemented using three main classes:

### 1. Player Class
- Represents a player with a label (X or O) and color
- Implemented using NamedTuple for immutability

### 2. TicTacToeGame Class
- Handles core game logic
- Features:
  - Move validation
  - Win detection
  - Player toggling
  - Game state management
  - Board setup and reset

### 3. TicTacToeBoard Class
- Manages the GUI using Tkinter
- Components:
  - Game board grid
  - Status display
  - Menu bar
  - Click handlers
  - Board state visualization

## Development Process (Step by Step)

The game was developed incrementally across 5 steps:

1. **Step 1**: Basic game setup and board creation
   - Core game logic implementation
   - Basic GUI structure

2. **Step 2**: Player management and move processing
   - Player switching mechanism
   - Move validation

3. **Step 3**: Win detection and game state
   - Row, column, and diagonal win checking
   - Game state tracking

4. **Step 4**: GUI enhancements
   - Status display
   - Color coding
   - Button styling

5. **Step 5**: Final features
   - Menu implementation
   - Reset functionality
   - Win highlighting
   - Tie game detection

## How to Play

1. Launch the game
2. Players take turns clicking empty squares
3. First player uses 'X' (blue), second uses 'O' (green)
4. Get 6 in a row (horizontal, vertical, or diagonal) to win
5. Status display shows current player and game state
6. Use File menu to restart or exit the game

## Technical Details

- Built with Python's standard library
- Uses Tkinter for GUI
- Object-oriented design pattern
- Type hints for better code readability
- Event-driven programming for user interactions

## Contributing

Feel free to fork this project and submit pull requests for improvements. Some areas for potential enhancement:

- AI opponent implementation
- Customizable board size
- Score tracking
- Sound effects
- Network multiplayer support

## License

This project is distributed under the MIT License. See the LICENSE file for more information.

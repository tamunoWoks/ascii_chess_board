## Interactive Chess Board (ASCII Version)
This is a Python program that displays and manages an interactive ASCII chessboard in the terminal. It allows you to place, move, remove, and reset chess pieces dynamically using simple commands.

### Features:
- ASCII Chess Board Rendering  
Displays an 8×8 chessboard with coordinates (a1–h8) and alternating black/white squares.
- Starting Chess Setup  
Automatically initializes with the standard chess starting positions.
- Interactive Commands
  - `move e2 e4` → Move a piece from one square to another.
  - `remove e2` → Remove the piece at the given square.
  - `set e2 wP` → Place a specific piece at a square.
  - `reset` → Reset the board to the standard setup.
  - `clear` → Clear all pieces from the board.
  - `fill wP` → Fill the entire board with a given piece.
  - `help` → Display help information.
  - `quit` → Exit the program.
- Custom Board Editing  
Experiment with custom setups for practice, puzzles, or analysis.

### Piece Codes:
- **Colors**
  - w = White
  - b = Black
- **Pieces**
  - P = Pawn
  - N = Knight
  - B = Bishop
  - R = Rook
  - Q = Queen
  - K = King

Example:
- wP = White Pawn
- bQ = Black Queen

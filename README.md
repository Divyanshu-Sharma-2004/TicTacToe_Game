# TicTacToe_Game
This is a simple **Tic-Tac-Toe** game built using **HTML**, **CSS**, and **JavaScript**. The game allows two players to take turns marking "X" and "O" in a 3x3 grid. The goal is to be the first player to align three of their marks in a row, either horizontally, vertically, or diagonally.

## Features:
- **Interactive Gameplay**: Players can click on the grid to mark "X" or "O".
- **Turn-based**: Players alternate between "X" and "O".
- **Win Detection**: The game checks for a winner after every move.
- **Reset Functionality**: Players can restart the game at any time.

## How It Works:
1. Players click on the empty boxes in the grid to make their moves.
2. The game alternates between "O" and "X" each turn.
3. After every move, the game checks for a winning combination.
4. If a player wins, a message displays the winner, and the game is disabled.
5. Players can reset the game using the reset button or start a new game.

## Code Breakdown:

### HTML Structure:
The HTML contains the layout for the Tic-Tac-Toe grid and buttons for resetting the game and starting a new game.

### JavaScript Logic:
1. **Event Listeners**: Each box in the grid has a click event listener attached. Players click on the boxes to make their moves.
2. **Win Patterns**: The game checks predefined win patterns to determine if any player has won.
3. **Game Functions**:
   - `resetgame()`: Resets the game to its initial state.
   - `disableBoxes()`: Disables all the boxes, preventing further moves once the game ends.
   - `enableBoxes()`: Enables all the boxes for a new game.
   - `showWinner()`: Displays the winner message and disables the game board.
   - `checkWinner()`: Checks if any player has won based on predefined win patterns.

### CSS Styling:
- **Grid Layout**: The grid is styled to have three rows and columns, with boxes arranged in a 3x3 matrix.
- **Colors**: "O" is styled with a green color (`#3a5a40`), and "X" is styled with a red color (`#ef233c`).
- **Message Display**: The winner message is shown in a hidden container that appears when a player wins.

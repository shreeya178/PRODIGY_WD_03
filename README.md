# Tic Tac Toe Game

This is a simple Tic Tac Toe game built with HTML, CSS, and JavaScript. Players can take turns placing their markers (X or O) on a 3x3 grid, and the game will determine if a player has won or if the game ends in a draw.

## Features

- Two-player mode (X and O)
- Displays current player's turn
- Detects win conditions and draws
- Restart button to play again

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To view and play the Tic Tac Toe game locally, follow these steps:

1. **Clone the repository** or download the HTML file.
2. Open the HTML file in your preferred web browser (e.g., Chrome, Firefox, Safari).
3. The game board will be displayed, and you can start playing by clicking on the cells.

## Code Overview

### HTML Structure
The main structure consists of:
- A status display indicating the current player's turn or the winner.
- A grid of cells for the Tic Tac Toe board.
- A restart button to reset the game.

### CSS Styles
The CSS styles are embedded in the `<style>` tag in the `<head>` section of the HTML document:
- **Body**: Centers the game board and sets a background image.
- **Container**: Centers the content and adjusts text alignment.
- **Board**: Uses CSS Grid to create a 3x3 layout for the game cells.
- **Cells**: Styled with a border, background color, and centered text.

### JavaScript Functionality
The JavaScript handles the game logic:
- **Variables**:
  - `currentPlayer`: Tracks whose turn it is.
  - `boardState`: Represents the state of the game board.
  - `isGameActive`: Indicates if the game is still ongoing.
- **Winning Conditions**: An array that defines the winning combinations.
  
#### Functions
- **handleCellClick(e)**: Handles the click event on each cell, updates the board state, checks for a win, and switches players.
- **checkWin(player)**: Checks if the current player has met any winning condition.
- **restartGame()**: Resets the game state and UI for a new game.

### Event Listeners
Event listeners are added to cells to handle player clicks and to the restart button to reset the game.

## Contact

For any inquiries or feedback, feel free to reach out to the project creator.

## License

This project is open-source and available under the MIT License. You are free to modify and use it as you wish.

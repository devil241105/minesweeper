# Minesweeper

This is a simple browser-based implementation of the classic **Minesweeper** game. The player tries to clear a grid without detonating hidden mines.

## Features

- Click on tiles to reveal empty spaces or mines.
- Use a flagging mode to mark suspected mines.
- Win the game by clearing all non-mined tiles.
- Lose the game by clicking on a mined tile.

## How to Play

1. **Left-click** on any tile to reveal what's underneath:
   - If it's a number, it shows how many mines are adjacent to that tile.
   - If it's an empty space, the adjacent tiles are automatically revealed.
   - If it's a mine, you lose the game.
2. **Flag mode**: To mark a tile that you think has a mine, toggle the flag mode by clicking the 🚩 button, then click on the tile to place a flag. Clicking again removes the flag.
3. The game ends when all non-mined tiles are revealed, or when you click on a mine.

## How to Run Locally

### Prerequisites
To run this project locally, you just need a modern web browser like Chrome, Firefox, Edge, or Safari.

### Steps to Run

1. **Download/Clone the repository**:
   - You can download the zip file or clone the repository using the command:
     ```
     git clone <repository-url>
     ```

2. **Navigate to the project directory**.

3. **Open the `index.html` file** in any modern web browser.

### Files
- **index.html**: The main HTML file that contains the structure of the page.
- **minesweeper.css**: The stylesheet that defines the layout and styling of the game board.
- **minesweeper.js**: The JavaScript file that contains the logic for the game.

## Project Structure

```
.
├── index.html        # Main HTML file
├── minesweeper.css   # CSS for styling the game
└── minesweeper.js    # JavaScript game logic
```

## Game Overview

- The game board consists of an 8x8 grid.
- There are 2 randomly placed hidden mines at the start of the game.
- The player must carefully click to avoid revealing mines.
- The player wins by clearing all the tiles without hitting any mines.

## Game Controls

- **Click** on tiles to reveal them.
- **Flag Button (🚩)**: Toggle flag mode to place or remove flags on suspected mines.

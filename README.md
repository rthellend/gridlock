# Gridlock Clone

A browser-based logic puzzle game built with vanilla HTML, CSS, and JavaScript. This project is a digital clone of the classic "Gridlock" board game (distinct from the traffic-jam style games).

## About the Game

The objective of Gridlock is to fit a specific set of puzzle pieces onto a 7x4 grid. It requires spatial reasoning and pattern matching to solve.

### Rules & Mechanics
* **The Board:** A fixed 7x4 grid featuring a specific pattern of three symbols: Squares, Circles, and Crosses.
* **The Pieces:** There are 14 unique piece shapes (Dominos and L-trominoes), each containing a combination of the three symbols.
* **Matching:** A piece can only be placed on the board if its symbols perfectly match the symbols on the grid cells underneath.
* **Manipulation:** Pieces can be rotated 90 degrees but cannot be flipped over.
* **Goal:** Completely cover the board using the subset of pieces provided for each level.

### Features
* **50 Puzzle Levels:** Includes 50 distinct challenges ranging in difficulty.
* **Cross-Platform:** Designed to work on both desktop (mouse) and mobile (touch) devices.
* **Interactive UI:**
    * Smooth drag-and-drop physics.
    * "Sticky" snap-to-grid logic with tolerance for easier placement.
    * Animated piece rotation.
    * Responsive layout that adjusts piece sizes to fit the screen.

## How to Play
1.  **Select a Level:** Use the dropdown menu in the header to choose a puzzle.
2.  **Rotate:** Tap or click a piece in the tray to rotate it 90 degrees.
3.  **Place:** Drag the piece onto the board. If the position is valid (symbols match and no overlap), it will snap into place.
4.  **Win:** The puzzle is solved when all pieces are successfully placed on the board.

## Technical Details & Credits

* **Tech Stack:** Pure HTML5, CSS3, and JavaScript contained in a single file (`gridlock.html`). No external libraries or frameworks were used.
* **Development:** This game was created through an iterative collaboration between the developer and **Google's Gemini**.
    * **Role of Gemini:** Acting as the coding engine, Gemini generated the complete source code, implemented the game logic (collision detection, state management), designed the CSS visual style (including the bevelled tile look), and refined the UX based on user feedback.

## Running the Game
Simply open `gridlock.html` in any modern web browser. No installation or server is required.

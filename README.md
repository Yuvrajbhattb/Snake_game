# Snake Game 🐍

A classic Snake game built using vanilla HTML5 Canvas, CSS, and JavaScript. The current version includes an auto-move feature where the snake calculates the closest path to the food while avoiding walls and its own body.

## Features

- **HTML5 Canvas:** Rendering of the game board, snake, and food.
- **Auto-Move AI:** The snake has a basic built-in auto-pathing algorithm to find food and try to avoid immediate collisions.
- **Dynamic Scoring:** Keeps track of the current score as the snake eats food.
- **Reset Functionality:** Easy restarting with a reset button.
- **Responsive Controls:** Supports arrow keys for manual control (though currently running auto-move logic).

## Technologies Used

- **HTML:** Structure of the game (Canvas, Score board, Reset Button).
- **CSS:** Simple styling and layout.
- **JavaScript (ES6):** Game logic, collision detection, movement, and drawing frames.

## How to Play Locally

1. Clone the repository or download the source code.
2. Open the `Index.html` file in any modern web browser.
3. Watch the snake auto-play or use arrow keys to change direction (depending on active logic).
4. Click "Reset" if you get a Game Over!

## Future Enhancements
- Toggling between fully Manual mode and Auto-bot mode.
- Improved AI for better pathfinding (e.g., A* Algorithm) to avoid boxing itself in.
- High score tracking utilizing LocalStorage.

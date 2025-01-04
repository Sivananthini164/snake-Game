Snake Game 🐍

A simple yet engaging Snake Game created using HTML, CSS, and JavaScript. The game challenges players to control the snake, eat food, and grow longer without colliding with the walls or itself.

🚀 Features

Smooth gameplay with increasing difficulty as the snake grows.
Tracks current score and high score using browser local storage.
Customizable grid-based game board.
Keyboard controls for smooth direction changes.

📂 Project Structure

Snake-Game/

├── index.html      # Main HTML structure

├── style.css       # Game styling

├── script.js       # Game logic and functionality

└── README.md       # Project documentation

🎮 How to Play

Use the Arrow Keys to control the snake's direction:
Up: Move up
Down: Move down
Left: Move left
Right: Move right
The goal is to eat the food (appears as a square on the board) and grow your snake.
Avoid hitting the walls or the snake's own body.
The game ends when the snake collides with itself or the walls

🛠️ Technologies Used

HTML5: Structure of the game.
CSS3: Styling the game elements.
JavaScript: Core logic for game mechanics.

📦 Installation

Clone this repository:

git clone https://github.com/Sivananthini164/snake-game.git
Open the index.html file in your favorite web browser to play the game.

🔧Customization

You can modify the grid size by adjusting the grid-template in the CSS file:
.play-board {
    grid-template: repeat(30, 1fr) / repeat(30, 1fr);
}
Change the game's speed by updating the interval in the setInterval function:
setInterval(initGame, 125); // Lower value = faster game


# Snake Game 🐍

A classic Snake game implemented in JavaScript, HTML, and CSS, featuring sound effects, scoring, and a high score tracking system. Eat food, grow the snake, and avoid collisions with the wall or yourself. 

## Demo

You can play the game [here](https://snake-game-angad.netlify.app/).

## Features

- **Responsive Controls**: Use arrow keys to move the snake in four directions.
- **Score Tracking**: Score increases with each piece of food eaten.
- **High Score**: High score saved using `localStorage` to retain data across sessions.
- **Sound Effects**: Unique sounds for eating food, game over, and movements.
- **Realistic Game Over Condition**: The game ends if the snake hits the walls or collides with itself.

## Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/angadp143/snake-game.git
   ```

2. Open the project directory:

   ```bash
   cd snake-game
   ```

3. Open `index.html` in your browser to start the game.

## How to Play

- Use the **Arrow Keys** to control the direction of the snake:
  - **Up Arrow**: Move up
  - **Down Arrow**: Move down
  - **Left Arrow**: Move left
  - **Right Arrow**: Move right
- **Goal**: Eat as much food as possible without hitting the wall or your own tail. Every time you eat food, your score increases, and the snake grows longer.
- **Game Over**: The game resets if you hit the wall or collide with yourself.

## Technologies Used

- **HTML**: Structure of the game.
- **CSS**: Styling the game board and snake elements.
- **JavaScript**: Game logic, collision detection, score, and high score tracking.

## Future Improvements

- **Difficulty Levels**: Add more levels with increasing speed.
- **Pause/Resume**: Include an option to pause and resume the game.
- **Mobile Compatibility**: Add touch controls for mobile users.
- **Themes**: Add options to change the color themes for the snake and board.
- **Leaderboard**: Implement a global leaderboard to track top scores across users.

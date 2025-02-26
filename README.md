# Snake-Game

This is a simple Snake Game implemented in Python using the `turtle` module. The game involves controlling a snake to eat food while avoiding collisions with the walls and itself. The score is tracked, and the game resets when the snake collides with the wall or its own body.

## Features
- Control the snake using arrow keys
- Food randomly spawns on the screen
- Score tracking with a high score stored in `data.txt`
- Automatic game reset upon collision with the wall or itself

## Requirements
Ensure you have Python installed. This game is built using the `turtle` module, which comes pre-installed with Python.

## How to Play
- Use the arrow keys to move the snake:
  - `Up Arrow` - Move up
  - `Down Arrow` - Move down
  - `Left Arrow` - Move left
  - `Right Arrow` - Move right
- Eat food to grow the snake and increase your score
- Avoid colliding with the walls and your own body
- The game resets upon collision, and the highest score is recorded

## File Structure
```
.
├── food.py        # Handles food placement
├── main.py        # Main game logic
├── scoreboard.py  # Manages score tracking
├── snake.py       # Handles snake movement and behavior
├── data.txt       # Stores high score
```

## Future Improvements
- Add sound effects
- Implement different difficulty levels
- Add power-ups or special food items
- Improve UI with better graphics

## Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request.


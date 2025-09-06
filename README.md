# Snake Game 🐍

A classic Snake game implementation using Python's Turtle graphics library.

## Description

This is a classic Snake game where the player controls a snake to eat food and grow longer. The game ends when the snake hits the wall or its own body. The objective is to achieve the highest score possible by eating as much food as you can.

## Features

- Classic snake gameplay mechanics
- Score tracking system
- Collision detection (walls and self-collision)
- Smooth snake movement
- Responsive keyboard controls
- Clean black background with white snake and blue food

## Requirements

- Python 3.x
- Turtle module (built-in with Python)

## How to Play

1. Run the game:
   ```bash
   python main.py
   ```

2. Use arrow keys to control the snake:
   - ↑ Up Arrow - Move up
   - ↓ Down Arrow - Move down
   - ← Left Arrow - Move left
   - → Right Arrow - Move right

3. Game Rules:
   - Eat the blue food to grow and increase your score
   - Avoid hitting the walls
   - Avoid hitting your own tail
   - Each food eaten increases your score by 1

## Project Structure

- `main.py` - Main game loop and initialization
- `snake.py` - Snake class handling movement and growth
- `food.py` - Food class for random food placement
- `scoreboard.py` - Scoreboard class for score display and game over message

## Game Controls

The snake cannot immediately reverse direction (e.g., if moving right, cannot immediately go left).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vipulkanade/snake_game.git
   cd snake_game
   ```

2. Run the game:
   ```bash
   python main.py
   ```

## Future Enhancements

- [ ] High score persistence
- [ ] Difficulty levels with varying speeds
- [ ] Different food types with different points
- [ ] Pause functionality
- [ ] Game restart option without closing window

## Author

Vipul Kanade
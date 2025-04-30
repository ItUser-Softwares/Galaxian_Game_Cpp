# Galaxian Game

A retro-style space shooter game inspired by the classic Galaxian, built with SFML.

![Screenshot from 2025-05-01 00-10-54](https://github.com/user-attachments/assets/829902fc-9677-4fa5-b5b6-8ed13d978c5b)
![Screenshot from 2025-05-01 00-11-05](https://github.com/user-attachments/assets/9417aae6-5b9f-41ad-99e1-eb0d18b93fcb)

## Features

- Welcome screen with game title and instructions
- Fast-paced arcade-style gameplay
- Player spaceship with controllable movement
- Multiple enemy types with different behaviors
- Scrolling space background
- Score tracking system
- Custom fonts and graphics

## Controls

- **Arrow Keys**: Move player ship left/right
- **Space Bar**: Fire projectiles
  
## Building the Project

```bash
# Clone the repository
git clone https://github.com/yourusername/galaxian-game.git
cd galaxian-game

# Create build directory
mkdir build && cd build

# Generate build files with CMake
cmake ..

# Build the project
cmake --build .

# Run the game
./galaxian
```

## Implementation Details

- **Background Scrolling**: Vertical parallax scrolling creates the illusion of movement through space
- **Player Movement**: Smooth, responsive controls with boundary detection
- **Enemy AI**: Formation-based movement patterns with attack sequences
- **Collision Detection**: Pixel-perfect collision detection for accurate gameplay
- **Font Rendering**: Custom font implementation for score display and menus

## Future Improvements

- Add power-ups and special weapons
- Implement multiple levels with increasing difficulty
- Add sound effects and background music
- Create a high score system
- Support for gamepad controllers

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Original Galaxian game by Namco
- SFML development team for the excellent multimedia library

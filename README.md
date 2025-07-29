# Snake Game - README

This is a modern, visually appealing Snake game implemented using HTML, CSS, and JavaScript. The game features smooth animations, responsive design, and an intuitive user interface.

## Features

- 🎮 **Classic Snake gameplay** with smooth controls
- 🌈 **Animated gradient background** with moving colors
- 📱 **Fully responsive design** that works on mobile and desktop
- 🏆 **Score tracking** with high score saved in localStorage
- ⚡ **Increasing difficulty** - game speeds up as you score more points
- 🕹️ **Multiple control options**:
  - Keyboard arrow keys
  - On-screen mobile controls
  - Start/Pause and Restart buttons
- ✨ **Visual effects**:
  - Pulsating food animation
  - Gradient-colored snake with distinct head
  - Glass-morphism game container
- 📶 **Network-free** - works completely offline

## How to Play

1. Open `index.html` in any modern web browser
2. Click "Start Game" to begin
3. Control the snake using:
   - **Arrow keys** on desktop
   - **On-screen directional buttons** on mobile
4. Guide the snake to eat the red food
5. Avoid colliding with yourself
6. Try to achieve the highest score possible!

## Game Rules

- Each food item gives you 10 points
- The snake grows longer with each food eaten
- Game speed increases as your score increases
- Colliding with your own body ends the game
- The snake can pass through walls (wraps to opposite side)

## Technical Implementation

### Files Structure
```
snake-game/
├── index.html        # Main game file (contains HTML, CSS, and JavaScript)
└── README.md         # This documentation file
```

### Technologies Used
- **HTML5** for game structure
- **CSS3** for styling and animations:
  - Flexbox and Grid layout
  - Gradient backgrounds
  - Keyframe animations
  - Responsive design with media queries
- **JavaScript** for game logic:
  - Game state management
  - Collision detection
  - Score tracking
  - localStorage for high score persistence

### Key Functions
- `initGame()` - Initializes game state
- `generateFood()` - Creates food at random positions
- `draw()` - Renders game elements
- `moveSnake()` - Handles snake movement and collision
- `gameLoop()` - Main game loop
- `startGame()` - Starts/pauses game
- `gameOver()` - Handles game over state

## Customization

You can easily customize the game by modifying these constants at the top of the JavaScript section:

```javascript
// Game constants
const GRID_SIZE = 20;        // Change grid dimensions
const CELL_SIZE = 20;        // Change cell size (affects overall game board size)
const INITIAL_SPEED = 150;   // Initial game speed (milliseconds)
const MIN_SPEED = 70;        // Maximum game speed (lower = faster)
```

## Browser Support

The game works on all modern browsers including:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Mobile browsers (Chrome for Android, Safari for iOS)

## Future Improvements

- Add different difficulty levels
- Implement different snake skins
- Add sound effects
- Create a leaderboard system
- Add power-ups and special food items

Enjoy the game! 🐍🍎

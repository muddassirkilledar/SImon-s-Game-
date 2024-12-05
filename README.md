# Simon's Game

This project is a web-based implementation of the classic Simon game, developed using **HTML**, **CSS**, and **JavaScript (jQuery)**. In this game, the player must follow a sequence of colors and repeat them in the correct order. As the player progresses, the sequence becomes increasingly longer and more challenging.

## How to Play

1. Open the game in your browser.
2. Press any key to start the game.
3. Watch the sequence of colors displayed.
4. Repeat the sequence by clicking the buttons in the same order.
5. If you repeat the sequence correctly, the game will continue with a longer sequence.
6. If you make a mistake, the game will end, and you can restart by pressing any key.

## Features

- Dynamic sequences of increasing length.
- Visual and audio feedback for user interactions.
- Game-over indication with restart functionality.

## Setup

1. Clone the repository or download the source code.
   ```bash
   git clone https://github.com/yourusername/simon-game.git
   ```
2. Open the `index.html` file in your browser to play the game.

## How It Works

1. **Game Initialization**:
   - When a key is pressed, the game starts, initializing the level and calling the `nextSequence` function.

2. **User Interaction**:
   - When a button is clicked, its color is added to the `userClickedPattern` array.
   - The game checks the user's input against the `gamePattern` using the `checkAnswer` function.

3. **Game Logic**:
   - The `nextSequence` function generates a random color, adds it to the sequence, and plays its associated sound.
   - If the user completes the sequence correctly, the next sequence is generated after a short delay.
   - If the user makes a mistake, the game plays a "wrong" sound, displays a game-over message, and resets.

4. **Audio and Animation**:
   - Each button click and sequence step triggers an associated sound and visual effect.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

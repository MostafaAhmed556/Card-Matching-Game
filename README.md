# Card-Matching-Game

## Overview
**Card-Matching-Game** is a C++ based console application that implements a simple 2D card matching game. Players take turns to flip cards and try to find matching pairs. The game continues until all pairs are matched. The player with the most pairs at the end of the game wins.

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Project Structure](#project-structure)
4. [Contributing](#contributing)
5. [License](#license)
6. [Special Thanks](#special-thanks)

## Introduction
This project is based on the classic concept of memory matching, where players flip over cards to find pairs. The game is designed to be played via a console application.

### Milestone 01
In the first milestone, the following classes and functions are implemented:
- **Card Class**: Represents an individual card in the game.
  - Methods:
    - `display()`: Displays the card’s number if face-up or a placeholder (*) if face-down.
  - Subclasses:
    - **StandardCard**: Represents a regular card with no special abilities.
    - **BonusCard**: Offers bonus points when matched.
    - **PenaltyCard**: Deducts points if mismatched.
- **Deck Class**: Represents the collection of cards in the game.
  - Methods:
    - `shuffle()`: Randomly shuffles the deck of cards.
    - `displayGrid()`: Displays the current layout of the cards in the grid.
- **Player Class**: Represents an individual participant in the game.
  - Methods:
    - `displayScore()`: Displays the player’s current score.
- **Game Class**: Manages the overall game flow and player interactions.
  - Methods:
    - `initializeGame()`: Initializes the game, shuffles the deck, and places cards to the grid.

### Milestone 02
In the second milestone, the core gameplay is implemented:
- **Player Turns and Card Flipping**: Players take turns to flip cards and try to find matching pairs.
- **Scoring Rules for Standard Cards**: Players gain points for matching cards.
- **Handling Special Cards**: Implement rules for Bonus and Penalty cards.
- **Game End and Winner Determination**: The game ends when all pairs are matched, and the player with the highest score wins.

## Getting Started
To get started with the Card-Matching-Game, follow these steps:

1. **Clone the Repository**
   ```sh
   git clone https://github.com/MostafaAhmed556/Card-Matching-Game.git
   ```

2. **Navigate to the Project Directory**
   ```sh
   cd Card-Matching-Game
   ```

3. **Build and Run the Application**
   - The application can be built and run using a C++ compiler (e.g., g++, clang).

## Project Structure
The project structure is organized as follows:

- `src/`: Contains the source code for the application.
- `.idea/`: Contains project-specific settings and configurations.
- `LICENSE`: The license file for the project.
- `README.md`: The main documentation file for the project.

## Contributing
Currently, there are no specific contributing guidelines available for this repository. If you wish to contribute, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. For more details, refer to the `LICENSE` file in the repository.

## Special Thanks
Special thanks to the following contributor(s) for their efforts and contributions to the project:
- [Abdullah Mahmoud](https://github.com/Abdullah-Mahmoud557)
- [Ahmed Hebesha](https://github.com/AhmedHebesha)

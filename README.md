# Chess Game

Welcome to the Chess Game! This Game is made by Prabhat Singh for Rebalance Technologies Assignment.
This is a classic two-player chess game implemented in Java. 
The game allows two players to compete against each other with standard chess rules.
Below you will find the instructions on how to set up, run, and play the game, as well as a brief overview of the code structure.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Running the Game](#running-the-game)
- [Game Rules](#game-rules)
- [Code Structure](#code-structure)
- [Contributing](#contributing)


## Features

- Two-player mode
- Graphical User Interface (GUI)
- Standard chess rules enforcement
- Move validation
- Check and checkmate detection

## Requirements

- Java Development Kit (JDK) 8 or higher
- An Integrated Development Environment (IDE) such as IntelliJ IDEA or Eclipse (optional but recommended)

## Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/prabhat8701/Chess.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd Chess
   ```
3. **Open the project in your IDE:**
   - If you are using an IDE like IntelliJ IDEA or Eclipse, open the project directory.

4. **Build the project:**
   - In your IDE, build the project to ensure all dependencies are resolved and the code compiles without errors.

## Running the Game

1. **Locate the main class:**
   - The main class is usually named `Chess` or similar and contains the `main` method.

2. **Run the main class:**
   - In your IDE, right-click the main class and select `Run`.

3. **Start playing:**
   - The game window should open, and you can start playing chess with another player.

## Game Rules

- **Objective:** Checkmate your opponent's king.
- **Moves:**
  - Each type of piece (pawn, rook, knight, bishop, queen, king) moves in a specific way.
  - Players take turns to move one piece at a time.
- **Special Rules:**
  - Castling
  - En passant
  - Pawn promotion
- **Endgame:**
  - The game ends when one player checkmates the other player's king.
  - Stalemate or draw conditions can also end the game.

## Code Structure

- **Main Class (`Main.java`):** The entry point of the game.
- **GUI Components (`Board.java`, `ChessPiece.java`, etc.):** Classes that handle the graphical representation of the game.
- **Game Logic (`Piece.java`, `MoveValidator.java`, etc.):** Classes that enforce the rules of chess and validate moves.
- **Utilities (`Inout.java`, `Constants.java`, etc.):** Helper classes and constants used throughout the game.

## Contributing

Contributions are welcome! If you have any ideas, bug fixes, or improvements, feel free to submit a pull request. Please ensure your code follows the existing code style and includes appropriate tests.

1. **Fork the repository:**
   ```sh
   git fork https://github.com/prabhat8701/Chess.git
   ```
2. **Create a new branch:**
   ```sh
   git checkout -b feature-name
   ```
3. **Make your changes and commit them:**
   ```sh
   git commit -am 'Add new feature'
   ```
4. **Push to the branch:**
   ```sh
   git push origin feature-name
   ```
5. **Submit a pull request:**


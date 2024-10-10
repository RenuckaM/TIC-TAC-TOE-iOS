# TIC-TAC-TOE-iOS (SwiftUI)

A simple and fun Tic-Tac-Toe game created using SwiftUI. This project demonstrates how to build a classic two-player game with a clean, intuitive user interface, utilizing SwiftUI's declarative UI framework.

# Screenshots

![image](https://github.com/RenuckaM/TIC-TAC-TOE-iOS/blob/main/Tic-tac-toe-2.jpg?raw=true![image](https://github.com/user-attachments/assets/b56b4018-7a7e-46f3-80a1-877c10540f6e)
)

## Features

- **Two-player mode:** Play against a friend on the same device.
- **Reset game:** Easily reset the game after a match.
- **Winning detection:** Automatically detects and highlights the winner or declares a draw.
- **Responsive UI:** The app is built with SwiftUI for a responsive and adaptive layout on different devices.
- **Score tracking:** Keeps track of each player's score throughout multiple rounds.

## Prerequisites

- **Xcode 12** or later
- **iOS 14** or later
- **Swift 5.3** or later

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-swiftui.git
   ```

2. Open the project in Xcode:
   ```bash
   cd tic-tac-toe-swiftui
   open TicTacToe.xcodeproj
   ```

3. Build and run the project on the simulator or your iOS device:
   - Select a target device or simulator.
   - Click on the "Play" button in Xcode to build and run the app.

## How to Play

1. Once the game starts, Player 1 (X) goes first.
2. Tap any of the 9 available spaces on the 3x3 grid to place your mark (X or O).
3. Players take turns until one player wins by getting three marks in a row (horizontally, vertically, or diagonally), or the game ends in a draw if the grid is full.
4. Press the "Reset" button to restart the game after a match.

## Project Structure

The project follows SwiftUI's declarative programming paradigm, making use of the following components:

- **Model:** Manages the game logic, player states, and winning conditions.
- **View:** SwiftUI views for rendering the game's interface, including the game board and player turn labels.
- **ViewModel:** Connects the model and view, handling user interaction and state updates.

## Contribution

Feel free to fork this repository and submit a pull request with improvements, bug fixes, or new features.



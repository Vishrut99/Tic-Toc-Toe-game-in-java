# Tic-Tac-Toe Game in Java

A classic Tic-Tac-Toe game implemented in Java with a graphical user interface using Swing. This interactive game allows two players to compete against each other on a 3x3 grid in a visually appealing desktop application.

## 🎮 Game Overview

The Tic-Tac-Toe game allows two players to compete against each other on a 3x3 grid. Players take turns placing their respective symbols (X or O) on the board. The game continues until one player gets three of their symbols in a row horizontally, vertically, or diagonally, or all squares are filled resulting in a tie.

## 🚀 Key Features

- **Graphical User Interface**: Visually appealing window with a 3x3 game board and text panel
- **Two-Player Gameplay**: Alternates between Player X and Player O for each turn
- **Win Detection**: Automatically checks for winning conditions horizontally, vertically, and diagonally
- **Tie Condition**: Detects when all squares are filled without a winner
- **Visual Feedback**: Changes color of winning tiles and displays game results
- **Current Player Display**: Shows whose turn it is during gameplay
- **Interactive Board**: Click-based tile selection system

## 🛠️ Technologies Used

- **Java**: Core game logic and application structure
- **Swing**: Graphical user interface components (buttons, labels, panels)
- **AWT (Abstract Window Toolkit)**: Color and font styling
- **Event Handling**: User interaction detection for tile clicks

## 🎯 Game Rules

1. The game is played on a 3x3 grid
2. Player X always goes first
3. Players take turns placing their symbol (X or O) in empty squares
4. The first player to get 3 of their symbols in a row (horizontally, vertically, or diagonally) wins
5. If all 9 squares are filled without a winner, the game ends in a tie

## 🏃‍♂️ How to Run

1. **Prerequisites**: Ensure you have Java Development Kit (JDK) installed on your system
2. **Clone the repository**:
   ```bash
   git clone https://github.com/Vishrut99/Tic-Toc-Toe-game-in-java.git
   ```
3. **Navigate to the project directory**:
   ```bash
   cd Tic-Toc-Toe-game-in-java
   ```
4. **Compile the Java files**:
   ```bash
   javac *.java
   ```
5. **Run the game**:
   ```bash
   java TicTacToe
   ```

## 🎨 User Interface

The game features a clean and intuitive interface with:
- A 3x3 grid of clickable buttons representing the game board
- A text panel at the top showing current player turn and game results
- Color-coded feedback for winning combinations
- Responsive button interactions

## 🔧 Technical Implementation

The game utilizes object-oriented programming principles with:
- Event-driven architecture for user interactions
- Efficient win condition checking algorithms
- Clean separation of game logic and UI components
- Proper state management for game flow

## 🏆 Win Conditions

The game checks for wins in all possible combinations:
- **Horizontal**: Three symbols in any row
- **Vertical**: Three symbols in any column
- **Diagonal**: Three symbols in either diagonal direction

## 🎭 Visual Feedback

- Winning tiles are highlighted with distinctive colors
- Current player is clearly displayed
- Tie games are prominently announced
- Smooth transitions between game states

## 🔄 Future Enhancements

Potential improvements for future versions:
- Single-player mode with AI opponent
- Score tracking across multiple games
- Different difficulty levels
- Sound effects and animations
- Customizable player names
- Game history and statistics

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements or bug fixes. All contributions are welcome!

## 📝 License

This project is open source and available under the MIT License.

## 📧 Contact

**Vishrut Lathiya**  
Email: [vishrutpatel50@gmail.com](mailto:vishrutpatel50@gmail.com)

---

*Enjoy playing this classic game! 🎯*

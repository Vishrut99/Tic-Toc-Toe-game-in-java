# Tic-Toc-Toe-game-in-java
The Tic Tac Toe game allows two players to compete against each other on a 3x3 grid. Players take turns placing their respective symbols (X or O) on the board. The game continues until one player gets three of their symbols in a row horizontally, vertically, or diagonally, or all squares are filled resulting in a tie.
Technologies Used:
Java: The entire game logic and user interface are implemented in Java.
Swing: The Swing library is used to create the graphical user interface, including the game board, buttons, and labels.
AWT (Abstract Window Toolkit): AWT is used for color and font settings in the game.
Event Handling: The code utilizes event handling mechanisms to detect user interactions, such as clicking on the game board tiles.
Key Features:
Graphical User Interface: The game is presented in a visually appealing window with a 3x3 game board and a text panel displaying the current player's turn and the game result.
Player Turns: The game alternates between player X and player O for each turn.
Win Conditions: The code checks for winning conditions horizontally, vertically, and diagonally. If a player gets three of their symbols in a row, they are declared the winner.
Tie Condition: If all squares are filled without a winner, the game ends in a tie.
Visual Feedback: The game provides visual feedback by changing the color of the winning tiles or displaying "Tie!" in case of a tie.

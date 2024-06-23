Project Documentation
1. Intended Logic and Efficient Code Implementation
The provided code is a basic implementation of a Tic Tac Toe game in Python. It demonstrates how to structure a game, handle user inputs, and check for winning conditions.

2. Programming Fundamentals
The code utilizes several fundamental programming constructs:

Classes and Objects: The TicTacToe class encapsulates all game-related functionalities.
Control Flow: It uses loops and conditionals to manage the game flow and check for win conditions.
Functions: Methods are defined within the class to modularize the game's logic.

3. Project Logic Plan
Below is the flowchart that represents the logic of the Tic Tac Toe game:

                +---------------------------------+
                | Start                           |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Initialize game board           |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Players choose markers          |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Display board                   |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Player 1 turn                   |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Player 1 chooses position       |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Place marker and check win/tie  |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Player 2 turn                   |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Player 2 chooses position       |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Place marker and check win/tie  |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | Replay?                         |
                +---------------------------------+
                              |
                              v
                +---------------------------------+
                | End                             |
                +---------------------------------+

4. Validation and Error Fixes
4.1 Error-based Fixes
Ensured the clearoutput method clears the screen correctly.
Checked user input validity in player_input and player_choice methods.
4.2 Manual Testing
Manual testing was done by running the script and playing the game multiple times to check for bugs and validate the flow.
Used PEP8 validator for code style and adherence to Python standards.
5. Code Separation
Application Code: The entire TicTacToe class.
External Code: No external libraries or tutorials were used in this implementation.
7. Implementation Efficiency
The code efficiently handles game logic, user input, and board state checks.
The win conditions are checked using a simple and readable set of conditions.
8. Documentation of Libraries and Rationale
8.1 Necessary Libraries
No external libraries are required for this basic implementation.
8.2 Project Outcomes
The game correctly initializes, processes user inputs, checks for win conditions, and offers replay functionality.
Screenshots demonstrate a successful run of the game (not included here but should be captured during manual testing).
8.3 Project Rationale
The project aims to provide a simple, interactive command-line Tic Tac Toe game. It is designed to be user-friendly and demonstrate basic programming constructs for educational purposes.

9. Deployment Procedure
9.1 README Deployment Section
Clone the Repository: git clone <repository-url>
Navigate to the Directory: cd tic-tac-toe
Run the Game: python tictactoe.py
By following these steps, the user can deploy and play the Tic Tac Toe game on their local machine.

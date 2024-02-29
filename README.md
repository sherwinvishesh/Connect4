
# Connect Four Game

This repository contains a Prolog implementation of the classic game Connect Four. Connect Four is a two-player connection board game in which the players choose a color and then take turns dropping colored discs into a grid. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

## Getting Started

### Prerequisites

To run the Connect Four game, you need to have Prolog installed on your system. 

### Installation

#### Option 1: GNU Prolog (Recommended)

1. **Install GNU Prolog:**
   - For Linux users:
     ```bash
     sudo apt-get install gprolog
     ```
   - For macOS users:
     ```bash
     brew install gnu-prolog
     ```
   - For Windows users, download the installer from [GNU Prolog website](http://www.gprolog.org/#download).

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/sherwinvishesh/Connect4.git
   ```
3. **Navigate to the directory:**
   ```bash
   cd Connect4
   ```

#### Option 2: Online Compiler

If you prefer not to install GNU Prolog locally, you can use an online Prolog compiler such as [SWISH](https://swish.swi-prolog.org/) or [tutorialspoint](https://www.tutorialspoint.com/execute_prolog_online.php). However, note that online compilers may have limitations on file size and execution time.

## Usage

### Running the Game

1. **Start GNU Prolog in terminal:**
   ```bash
   gprolog
   ```

2. **Load the game:**
   ```prolog
   consult('/path/to/connect4.pl').
   ```

3. **Start the game:**
   ```prolog
   connect4.
   ```

4. **Follow the prompts to make moves.**

### Game Rules

- **Objective**: The objective of the game is to be the first player to connect four of your colored discs in a row, column, or diagonal on the game board.
  
- **Player Pieces**: 
  - You play as 'X' and the bot plays as 'O'.
  - Players take turns dropping their respective pieces into one of the seven columns of the board.

- **Gameplay**:
  1. **Player Turn**:
     - You will be prompted to enter the column where you want to drop your piece.
     - Input the column letter ('A' to 'G') to drop your piece in the corresponding column.
  
  2. **Bot Turn**:
     - After your move, the bot (playing as 'O') will make its move automatically.
     - The bot is programmed to make strategic moves to prevent you from connecting four pieces and to form its own winning combinations.

- **Winning**:
  - The game ends when either player successfully connects four of their pieces horizontally, vertically, or diagonally.
  - If you manage to connect four pieces before the bot, you win the game.
  - Conversely, if the bot connects four pieces first, you lose the game.

- **Draw**:
  - If the entire board fills up without either player achieving four in a row, the game is declared a draw.

- **Game Over**:
  - Once the game ends (either by a win, loss, or draw), the final game state is displayed, and you have the option to start a new game or exit.

- **Enjoy the Challenge**:
  - The bot is designed to provide a challenging opponent, so use your strategic skills to outsmart it and achieve victory!
  - Good luck, and have fun playing Connect Four against the bot!

## User Interface  

![Connect4 Screenshot](https://raw.githubusercontent.com/sherwinvishesh/Connect4/main/Public/Connect4%20Screenshot.png)

## Code Structure

- **`connect4.pl`**: Main Prolog file containing the game logic and rules.
- **`README.md`**: This file, providing instructions and information about the game.
- **`LICENSE`**: License information for the project.

## Contributing

Contributions to enhance this project are welcomed. Please feel free to fork the repository, make changes, and submit pull requests.

## Support

If you encounter any issues or have any questions, please submit an issue on the GitHub issue tracker or feel free to contact me.


## License

Connect4 is open source and available under the [MIT License](LICENSE).

## Acknowledgments


- Thanks to everyone who visits and uses this page. Your interest and feedback are what keep us motivated.
- Special thanks to all the contributors who help maintain and improve this project. Your dedication and hard work are greatly appreciated.
- Special acknowledgment to Ramon Viñas for their project [connect-4-prolog](https://github.com/rvinas/connect-4-prolog). It served as a significant inspiration for this project, demonstrating the powerful impact of Prolog.

## Connect with Me

Feel free to reach out and connect with me on [LinkedIn](https://www.linkedin.com/in/sherwinvishesh) or [Instagram](https://www.instagram.com/sherwinvishesh/).


---

Made with ❤️ by Sherwin


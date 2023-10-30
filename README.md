# Mastermind Game

![Mastermind Game](./src/main/resources/Mastermind.mp4)

## Overview
Mastermind Java Game is an engaging and interactive console-based application inspired by the classic Mastermind board game. It challenges players to test their logic and deduction skills by guessing a secret code within a limited number of attempts. In our latest update, we've introduced three new algorithms: random, minimax, and DFS (Depth-First Search) to enhance the gameplay experience and offer varied strategic approaches for players.

## Project Information
Bucknell University
Lewisburg, PA

### Course Info
Instructor: Professor Stough
Semester: 2023FW
Class: CSCI 205 - Software Engineering & Design

### Team Members
- [Nolan Lwin](https://github.com/i-am-nolan25/) - Class of 2026, Computer Science
- [Chang Min Bark](https://github.com/changminbark) - Class of 2026, Computer Science and Engineering

## Key Features 🚀
- **Code Generation**: The game generates a secret code made up of a sequence of four number pegs for the player to guess.
- **Player Input**: Players enter their guesses through the console, trying to crack the secret code within a specified number of attempts.
- **Feedback System**: After each guess, the game provides feedback to the player, indicating how accurate their guess was. Feedback typically consists of clues, indicating correct pegs in the correct position (represented as *) and correct pegs in the wrong position (represented as +).
- **Limited Attempts**: Players have a limited number of attempts (up to 12 attempts) to guess the correct code, adding an element of strategy and urgency to the gameplay.
- **Random Algorithm**: The game generates a random code for the player to guess.
- **Minimax Algorithm**: The game generates a code based on the minimax algorithm for the player to guess.
- **DFS Algorithm**: The game generates a code based on the DFS algorithm for the player to guess.

## Installation ⚙️

### Prerequisites
- Java 8 or later

### Steps
1. **Clone the Repository**
   ```
   git clone https://github.com/i-am-nolan25/Mastermind.git
   cd hw01
   ```

2. **Compile and Run**
Open the project in your preferred IDE and navigate to the following path to run the game.
    ```
    ./src/main/java/hw01/game/Main.java
    ```

## Usage
After launching the game, follow these steps:

1. Choose how you want to play the Mastermind game through 4 options: User, Random, Minimax, and DFS.
2. If user, input your guesses based on the feedback provided by the game.
3. Try to guess the correct sequence within the allotted 12 attempts.
4. Enjoy and challenge your logic and deduction skills!

2. If one of the algorithms, enter the number of games you want to simulate.
3. See the statistics of the algorithm such as the shortest and longest guess for the Mastermind game within the number of games you simulate.
4. Enjoy and test how efficient each algorithm is.

## Dependencies
Java Runtime Environment (JRE)

## Contributing
Contributions to the Mastermind Java Game are welcome. Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (git checkout -b feature-yourfeature).
3. Make your changes and commit (git commit -am 'Add some feature').
4. Push to the branch (git push origin feature-yourfeature).
5. Create a new Pull Request.

## License 📄
This project is licensed under the [MIT License](https://github.com/i-am-nolan25/Mastermind/blob/main/LICENSE).

## Troubleshooting 🛠️
Please create a new [issue](https://github.com/i-am-nolan25/Mastermind/issues/new).

## Contact 📬
For any inquiries, feedback, or collaboration opportunities, please feel free to reach out to me through my [email](nl020@bucknell.edu) or [LinkedIn](https://www.linkedin.com/in/naing-oo-lwin-nolan/).
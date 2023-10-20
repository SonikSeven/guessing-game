# Gessing Game

Welcome to the Guess the Number game! This is a simple, yet entertaining command-line game written in Rust. In this game, your task is to guess a randomly generated number between 1 and 100. After each guess, you'll receive feedback on whether your guess is too low, too high, or correct. Once you guess the number correctly, you win the game!

## Requirements

- [Rust](https://www.rust-lang.org/tools/install)

## Installation

This application is written in Rust, so you'll need Rust installed on your computer to build it. If you don't have Rust installed, you can download it from [rust-lang.org](https://www.rust-lang.org/tools/install).

To install this project, follow these steps:

1. Clone the repository to your local machine:
   
   ```
   git clone https://github.com/SonikSeven/guessing-game.git
   ```
   
2. Navigate to the cloned repository:
   
   ```
   cd guessing-game
   ```

3. Build the project with Cargo:
   
   ```
   cargo build --release
   ```

## How to Run

Run the executable in `./target/release/`.

## How to Play

1. **Start the game:** Once you've executed the `cargo run` command, the game will start, and you will see a message prompting you to guess a number.

2. **Input your guess:** Type a number between 1 and 100 and press Enter.

3. **Receive feedback:** The game will immediately inform you if your guess is too high, too low, or correct.

- If your guess is too high, you will see the message, "Too big!"
- If it's too low, you'll see, "Too small!"
- Guess correctly, and you'll see, "You win!"

4. **Repeat:** Keep guessing until you get the number right. The game will continue to prompt you for guesses until you win.

## About

This project is based on content from "The Rust Programming Language" book by Steve Klabnik and Carol Nichols. The book is an excellent resource for learning Rust, and this project aims to implement some of the concepts and examples presented in the book.

## Attribution

- **Book Title**: The Rust Programming Language
- **Authors**: Steve Klabnik and Carol Nichols
- **Publisher**: No Starch Press
- **Website**: [The Rust Programming Language](https://doc.rust-lang.org/book/)

## License

This project is licensed under the [CC-BY 4.0 License](LICENSE.txt).

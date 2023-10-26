# StarWords Constructor

**StarWords Constructor** is a command-line game that challenges players to guess the names of famous Star Wars characters one letter at a time. It utilizes Node.js and Inquirer for user input and interaction.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Gameplay](#gameplay)
- [Game Logic](#game-logic)
- [Restarting the Game](#restarting-the-game)
- [Dependencies](#dependencies)

## Installation

To run StarWords Constructor on your local machine, follow these steps:

1. Clone the repository to your local system.
2. Navigate to the project directory using the command line.
3. Install the necessary dependencies by running:

   ```
   npm install
   ```

## Usage

To start playing StarWords Constructor, execute the following command in your terminal:

```
node index.js
```

The game will prompt you to guess letters for a random Star Wars character's name. You have 10 chances to guess the correct letters.

## Gameplay

- You will be presented with a series of underscores, each representing a letter in the Star Wars character's name.
- Enter a letter (a-z) to make a guess.
- The game will inform you if your guess was correct or incorrect.
- The number of remaining guesses is displayed.
- The letters you have already guessed are listed.

## Game Logic

- The game selects a random Star Wars character's name from the list.
- The selected word is passed through the StarWords constructor.
- The game checks if your guessed letters are correct.
- You win the game if you guess all the letters correctly.
- You lose the game if you run out of guesses.

## Restarting the Game

After winning or losing, you will be prompted to choose whether to play again or exit the game.

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): Used for user input and interactions.
- [letter.js](./letter.js): Contains the `letter` constructor used for creating letter objects.
- [word.js](./word.js): Contains the `Word` constructor used for creating word objects for the game.

---

Have fun guessing Star Wars characters' names with StarWords Constructor! May the Force be with you!
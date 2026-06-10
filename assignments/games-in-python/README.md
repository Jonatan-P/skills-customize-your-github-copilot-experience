# 📘 Assignment: Games in Python

## 🎯 Objective

Build a Hangman-style game in Python that uses loops, conditionals, string handling, and user input to create an interactive experience.

## 📝 Tasks

### 🛠️ Create the game loop

#### Description
Write the main game loop to repeatedly prompt the player for letter guesses and update the displayed word state.

#### Requirements
Completed program should:

- Randomly choose a secret word from a predefined list
- Display the current word progress using underscores for hidden letters
- Prompt the player to enter a single letter on each turn


### 🛠️ Track guesses and game state

#### Description
Manage correct and incorrect guesses, including a limited number of attempts and win/lose conditions.

#### Requirements
Completed program should:

- Track letters the player has guessed correctly and incorrectly
- Decrease remaining attempts for wrong guesses
- End the game when the word is fully guessed or no attempts remain
- Show a win message if the player guesses the word, or a lose message with the secret word if attempts run out


### 🛠️ Improve player feedback

#### Description
Enhance the game by showing helpful feedback on each guess and preventing repeated guesses from affecting attempts.

#### Requirements
Completed program should:

- Inform the player when a guess is correct or incorrect
- Prevent duplicate letter guesses from using up attempts
- Show the list of guessed letters and remaining attempts after each round

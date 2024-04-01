# RPS-game-
It is a rock ,paper,scissor game using python
Rock, Paper, Scissors Game in Python

The Rock, Paper, Scissors game is a classic hand game usually played between two people, where each player simultaneously forms one of three shapes with an outstretched hand. The possible shapes are rock, paper, and scissors. The game has simple rules: rock beats scissors, scissors beats paper, and paper beats rock. If both players choose the same shape, the game is a tie.

Program Description:

1. Imports:
   - The program starts by importing the `random` module, which is used to generate random choices for the computer player.

2. Function Definitions:
   - `determine_winner(player_choice, computer_choice)`: This function takes the player's choice and the computer's choice as arguments, compares them according to the rules of the game, and determines the winner.
   
3. Main Function (`main()`):
   - The `main()` function initializes a list `choices` containing the possible choices for the game (rock, paper, and scissors).
   - It runs an infinite loop to allow the game to continue until the player decides to quit.
   - Inside the loop, it prompts the player to input their choice or type 'quit' to end the game.
   - It validates the player's input and ensures it is one of the valid choices (rock, paper, scissors), or quits the game if the input is 'quit'.
   - If the input is valid, it randomly selects the computer's choice from the `choices` list.
   - It prints both the player's and computer's choices, and the result of the game determined by the `determine_winner()` function.
   - The loop continues until the player decides to quit.

4. Game Execution:
   - When the program is executed, it welcomes the player to the Rock, Paper, Scissors game and prompts them to make a choice.
   - It continues prompting for the player's input until they decide to quit.
   - After each round, it displays the player's choice, the computer's choice, and the result of the game (win, lose, or tie).
   - The game ends when the player chooses to quit.

This Python program provides a simple implementation of the Rock, Paper, Scissors game, allowing players to enjoy the timeless hand game against a computer opponent.

# Game Hangman
Hangman is a classic word-guessing game implemented in JavaScript. Players attempt to uncover a hidden word by guessing one letter at a time.
The game features a simple user interface where players receive immediate feedback on their guesses, tracking both correct and incorrect attempts.
The game concludes successfully when the player uncovers the word or ends due to the exhaustion of allowed attempts. This implementation is designed to be simple, engaging, and easily integrated into web pages.

## Designing the game
1. Randomly choose a word
2. Request player input for their guess
3. End the game at the player's request
4. Check if the entered response is a letter
5. Keep track of guessed letters
6. Show the player how many letters they have guessed and how many remain
7. End the game if the word is guessed

## Using pseudocode for game design
Select a random word
While the word is not guessed {
 Show the player the current state of the game
 Request player input for their guess
 If the player wants to exit the game {
   Exit the game
 }
 Else if the input is not a single letter {
   Inform the player that they should enter a letter
 }
 Else {
   If such a letter exists in the word {
     Update the game state by substituting the new letter
     }
   }
 }
Congratulate the player when the word is guessed
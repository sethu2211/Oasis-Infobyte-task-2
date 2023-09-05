# Oasis-Infobyte-task-2
NUMBER GUESSING GAME

Initialize game parameters:

Set lowerBound to the minimum possible number.
Set upperBound to the maximum possible number.
Set maxAttempts to the maximum number of attempts allowed per round.
Initialize totalScore to keep track of the player's score.
Initialize playAgain to true to start the game.
Display a welcome message.

Start a loop to manage the game rounds:

Generate a random number between lowerBound and upperBound (inclusive) and store it in generatedNumber.
Initialize attempts and userScore to 0 for the current round.
Display a message indicating the range of numbers the player should guess.

Start a loop to manage the player's attempts:

Prompt the player to enter their guess.
Increment attempts by 1.
If the player's guess matches generatedNumber:
Display a congratulations message, showing the number of attempts.
Calculate the player's score for the current round based on the remaining attempts and update userScore.
Update totalScore by adding userScore.
Break out of the loop.
If the player's guess is less than generatedNumber, inform them to try a higher number.
If the player's guess is greater than generatedNumber, inform them to try a lower number.
If the player has used all allowed attempts (attempts == maxAttempts):
Display a message indicating that the player has run out of attempts and reveal the correct number.
Break out of the loop.
Display the player's score for the current round and their total score.

Ask the player if they want to play again. Accept their input (either "yes" or "no") and update the playAgain variable accordingly.

Repeat the game round if playAgain is true.

When the player decides not to play again, display a thank-you message and close the scanner.

End the game.

This algorithm outlines the flow of the "Guess the Number" game, including generating random numbers, managing user input, scoring, and playing multiple rounds until the player chooses to quit.

# number-guessing-game-js-html
Guess the number game. From https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash

Generate a random number between 1 and 100.
Record the turn number the player is on. Start it on 1.
Provide the player with a way to guess what the number is.
Once a guess has been submitted first record it somewhere so the user can see their previous guesses.
Next, check whether it is the correct number.
If it is correct:
Display congratulations message.
Stop the player from being able to enter more guesses (this would mess the game up).
Display control allowing the player to restart the game.
If it is wrong and the player has turns left:
Tell the player they are wrong.
Allow them to enter another guess.
Increment the turn number by 1.
If it is wrong and the player has no turns left:
Tell the player it is game over.
Stop the player from being able to enter more guesses (this would mess the game up).
Display control allowing the player to restart the game.
Once the game restarts, make sure the game logic and UI are completely reset, then go back to step 1.

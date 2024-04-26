# 1A2B-App
This Android app implements a digital version of the classic Mastermind game. The game involves guessing a secret code based on provided hints until the correct code is determined within four rounds.

# Game Rules and Features
Number Generation Rule
Generates a random four-digit code with non-repeating digits (including leading zero).
Hint Generation (A and B)
Provides hints based on the user's guess:
'A' indicates correct digit and position.
'B' indicates correct digit but wrong position.

# Navigation and Game Flow
Start Fragment:/n
Pressing the "START" button navigates to the guessing fragment (guessFragment) to begin the game.

Guess Fragment:

Displays current score, round number, and remaining guess attempts.
Allows users to input a four-digit guess and limits input to valid format.
Pressing "GUESS" button displays the hints for the current guess.

Result Fragment (After fourth round):
Shows the game record, including answers and guess attempts for each round.
Provides options to start a new game (NEXT GAME) or return to the home screen (HOME).
History and Record Keeping:
History Fragment:
Lists game scores for each played session.
Allows navigation to detailed game history (stageHistoryFragment).
Stage History Fragment:
Lists answers and guess attempts for each round of a specific game.
Allows navigation to detailed round history (recordHistoryFragment).
Record History Fragment:
Lists each guess attempt with corresponding hints for a specific round.
# Additional Features
Supports orientation changes to maintain current game state.
Ensures robust error handling and user feedback for invalid inputs and game actions.

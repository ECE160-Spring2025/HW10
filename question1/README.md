## Question 1

Write the game "Wheel of Fortune" in Python using **object-oriented programming (OOP)** principles (AKA classes). For those of you who are not familiar with the game show, you can read more about it on Wikipedia.

Below are the requirements:
- Use **classes** to structure your code. At a minimum, you should have the following classes:
  - `Player`: Represents a player in the game, including their name and score.
  - `Wheel`: Represents the wheel, including the dollar amounts and special spaces (e.g., $5000, $500, bankrupt, lose a turn).
  - `Game`: Represents the overall game logic, including the puzzle, used letter board, and turn management.
- Allow a user to enter their own puzzle.
- Have a used letter board.
- Have a wheel that provides a random dollar amount from $500 to $5000.
- Allow 3 players to play and take turns.
- Keep track of the 3 players' scores.
- Player 1 will start the game. He/she will spin the wheel.
- Player 1 will call a letter and if there is a letter, fill in the blanks, add the letter in the used letter board, and give player 1 the money they landed on times the number of letters in the game. If the letter is not in the puzzle, the next player will play.
- For simplicity, all letters can earn money (unlike in the real show, where a vowel costs $250).

Bonus:
- (+10) Write an AI (computer player) that plays relatively intelligently.
- (+10) Include a bankrupt space and a lose a turn space on the wheel.
- (+10) Allow a user to solve the puzzle at any time.
- (+10) Allow a user to buy a vowel for $250 and restrict a user from calling a vowel if he/she decided to spin the wheel.

### Additional Notes:
- Your implementation will be graded on **code quality** and **code output**.
- Make sure to use appropriate methods and attributes for each class.

### Execution Steps:

Output:
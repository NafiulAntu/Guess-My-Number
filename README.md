[Live link] (https://nafiulantu.github.io/Guess-My-Number/)
# Guess My Number

A simple browser game where you try to guess a hidden number between 1 and 20.

## Features

- Random secret number generation on every new game
- Score starts at 20 and decreases by 1 for each wrong guess
- Feedback messages for:
  - no input
  - guess too high
  - guess too low
  - correct guess
  - game over
- High score tracking during the current browser session
- Reset button (`Again!`) to start a new round

## How To Play

1. Enter a number from 1 to 20.
2. Click `Check!`.
3. Read the hint message:
   - `Too high!` means your guess is above the secret number.
   - `Too low!` means your guess is below the secret number.
4. Keep guessing until you find the correct number or your score reaches 0.
5. Click `Again!` anytime to restart with a new secret number.

## Scoring

- Initial score: 20
- Wrong guess: -1 point
- Correct guess: current score is compared to high score
- If score reaches 0: you lose the round

## Project Files

- `index.html`: game structure and UI elements
- `style.css`: game styling
- `script.js`: game logic and interactions

## Run Locally

1. Open `index.html` in any modern web browser.
2. Start guessing.

No build tools or dependencies are required.

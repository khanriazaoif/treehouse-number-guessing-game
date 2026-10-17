# Unit 1 – The Number Guessing Game

Treehouse Python Development Techdegree, Project 1 (~2 hours).
Source: https://teamtreehouse.com/projects/the-number-guessing-game (rubric pulled 2026-10-17)

A console game: the player guesses a random number within a range, gets "higher"/"lower"
hints until correct, then sees how many attempts it took.

> Use ONLY concepts covered in the Unit 1 courses so far.

## Run it

```bash
source .venv/bin/activate   # once per terminal session
python guessing_game.py
```

## Before you start
- [ ] Finish the Unit 1 curriculum
- [x] GitHub repo created — commit at key stages, not just at the end
- [x] Official starter `guessing_game.py` downloaded from the project page (number-guessing-game-v1.zip)
- [ ] Skim the resource: Python docs for `random.randint`

## Instructions (Meets Expectations)
- [ ] `import random` at the top of the file
- [ ] `start_game()` function holds the whole game loop
- [ ] Welcome / intro message when the script runs
- [ ] Generate a random winning number within the range and store it in a variable
- [ ] `while` loop — keep prompting until the guess is correct
- [ ] Feedback after each wrong guess — exact wording in rubric: **"It's higher"** / **"It's lower"**
- [ ] Attempts counter, shown at the end once the player guesses correctly
- [ ] Goodbye message when the game ends
- [ ] Handle bad input with exceptions — non-numbers **and floats** (e.g. `4.5`) must not crash it

## Extra credit (Exceeds Expectations — all 4 required)
- [ ] Out-of-range guess (e.g. 12 when range is 1–10) → tell the player and let them retry
- [ ] After winning, ask "play again?" — yes loops back, no shows the goodbye message
- [ ] Show the current high score (fewest attempts) at the start of each game
- [ ] New random number every time they play again

## Grading rubric
| Area | Meets | Exceeds |
|---|---|---|
| Script execution | Runs; all exceptions caught — no crashes | — |
| Intro | Welcome message shown when run | — |
| Random number | Random number within range | New number each replay |
| User input | Prompted for guess; non-numbers handled by exceptions; bad input never exits the app | Out-of-range numbers rejected with "not a valid option, try again" |
| Feedback | "It's higher" / "It's lower" after each guess | — |
| Tries | Attempt count shown at end of each game | High score shown at start of each new game |
| End game | Goodbye/quit message | Play-again prompt (yes → replay, no → goodbye) |

## Finishing checklist
- [ ] Replace the starter comments with your own comments describing your code
- [ ] Consistent spacing/indentation
- [ ] QA: play it as a user — try letters, `4.5`, blanks, `0`, `11`, `-3`, the correct number first try, replay several times
- [ ] Optional: post the GitHub link in Slack `#review-my-project` for a second pair of eyes
- [ ] Claude code review against this rubric (doesn't write it for you)
- [ ] **In your submission comments, state which grade you're going for** (Meets vs. Exceeds).
      Passing grades are final — miss one Exceeds item and you keep "Meets" with no second try.

## Note
Project reviews are **not available during the Treehouse trial** — submission requires upgrading
to a paid plan.

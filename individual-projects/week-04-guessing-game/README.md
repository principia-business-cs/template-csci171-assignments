# Week 04: Guessing Game

## Focus

while loops, sentinels, counters, and debugging loops.

## Textbook Grounding

Official textbook: *How to Think Like a Computer Scientist: Learning with Python 3*.

- Primary reading: Chapter 7, Iteration
- Main ideas: while loops, sentinels, counters, and debugging loops
- Textbook link: <https://openbookproject.net/thinkcs/python/english3e/iteration.html>

## Branch Name

Use this exact feature branch name for this assignment:

```text
week-04-guessing-game
```

Open your pull request from `week-04-guessing-game` into your repo's `main` branch. Submit the PR link in Canvas when this assignment is collected.

## Required Friday Project

Build a number guessing game where the player guesses a secret number and receives feedback until the game ends.

The goal is not to build the largest possible program. The goal is to show that you can use this week's textbook concepts correctly and explain your choices.

## Requirements I Will Check

Your program must include all of these:

- [ ] Use a `while` loop to repeat guesses.
- [ ] Use a sentinel value or correct-guess condition to stop the loop.
- [ ] Ask for numeric input and convert it with `int()`.
- [ ] Use conditionals to print too high, too low, or correct feedback.
- [ ] Track the number of guesses with a counter variable.
- [ ] Prevent the game from continuing forever after the correct answer.
- [ ] Print a final summary that includes the number of guesses.
- [ ] Include at least three test cases in `notes.md`, including a win path and a repeated-wrong-guess path.

## Test Cases Required In `notes.md`

Include at least three tests like this:

```text
Test 1
Inputs or actions: what you typed, clicked, or changed
Expected result: what should happen
Actual result: what happened when you ran it
```

Your tests should show different paths or cases. Do not test the same behavior three times.

## Expected Result

A user can run your program, see clear output or interaction, and verify that the required concept is working.

## Stretch 1: Solid Extension

This is optional extra credit for students who have the required project working and want a manageable next step.

Requirements:

- [ ] Add difficulty levels that choose different number ranges.
- [ ] Print the selected range before guessing starts.
- [ ] Keep the required counter and final summary working.
- [ ] Add two more test cases for different difficulty levels.

## Stretch 2: Challenge Extension

This is optional extra credit for students who already know some programming and want a more demanding version of the same week's topic.

Requirements:

- [ ] Track the best score during one run of the program.
- [ ] Ask whether the player wants to play again.
- [ ] Use a nested loop or helper function to keep the replay logic readable.
- [ ] Add two more test cases for replay and best-score behavior.

## Submission Checklist

- [ ] My code runs before I submit.
- [ ] My branch name is exactly `week-04-guessing-game`.
- [ ] My `notes.md` includes at least three required test cases.
- [ ] My pull request is open into my repo's `main` branch.
- [ ] I submitted the PR link in Canvas.

## Files

- `starter.py`: start here
- `notes.md`: include planning notes and required test cases

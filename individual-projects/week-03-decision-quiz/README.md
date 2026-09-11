# Week 03: Decision Quiz

## Focus

Booleans, comparison operators, `if` / `elif` / `else`, multiple conditions, nested choices, input cleanup, and test cases.

## Textbook Grounding

Official textbook: *How to Think Like a Computer Scientist: Learning with Python 3*.

- Primary reading: Chapter 5, Conditionals
- Main ideas: Boolean expressions, comparison operators, logical operators, conditional execution, alternative execution, chained conditionals, and nested conditionals
- Textbook link: <https://openbookproject.net/thinkcs/python/english3e/conditionals.html>

## Branch Name

Use this exact feature branch name for this assignment:

```text
week-03-decision-quiz
```

Open your pull request from `week-03-decision-quiz` into your repo's `main` branch. Submit the PR link in Canvas when this assignment is collected.

## Required Friday Project

Create a short interactive quiz, recommendation tool, or branching prompt that uses conditionals to make decisions from user input.

The goal is not to build a huge program. The goal is to prove that you can use Python conditionals correctly and explain what each condition is checking.

## Requirements I Will Check

Your program must include all of these:

- [ ] Ask the user at least three questions with `input()`.
- [ ] Use `.strip()` or `.lower()` on at least one text input before comparing it.
- [ ] Use at least one equality comparison with `==`.
- [ ] Use at least one inequality comparison with `!=`, `<`, `<=`, `>`, or `>=`.
- [ ] Use at least one `if` / `else` decision.
- [ ] Use at least one `if` / `elif` / `else` chain with three or more possible paths.
- [ ] Use at least one multiple-condition expression with `and` or `or`.
- [ ] Track a score, category, or result variable that changes based on user answers.
- [ ] Print a final result that depends on the score, category, or result variable.
- [ ] Include at least three test cases in `notes.md` showing inputs you tried and the output you expected.

## Test Cases Required In `notes.md`

Include at least three tests like this:

```text
Test 1
Inputs: answer1, answer2, answer3
Expected result: high score / beginner recommendation / try again message
Actual result: what happened when I ran it
```

Your tests should show different paths through your conditionals. Do not test the same path three times.

## Expected Result

A user can run your program, answer the prompts, and get a result that clearly changes when different answers are entered.

## Stretch 1: Solid Extension

This is optional extra credit designed to show stronger mastery without turning the assignment into a giant project.

Requirements:

- [ ] Add input validation for at least one question. Example: if the user types something invalid, print a helpful message.
- [ ] Use both `and` and `or` somewhere in the program.
- [ ] Add at least two more test cases to `notes.md` that test your validation or multiple-condition logic.
- [ ] Keep the required project working.

## Stretch 2: Challenge Extension

This is optional extra credit for students who already know some programming and want a more interesting conditional challenge.

Requirements:

- [ ] Use a conditional expression, also called a ternary expression, at least once.

Example:

```python
message = "passing" if score >= 3 else "keep practicing"
```

- [ ] Add a replay option or a second round.
- [ ] Use a nested conditional or a helper function to keep the code readable.
- [ ] Add at least two more test cases to `notes.md` for the replay, ternary, or nested/helper logic.
- [ ] Keep the required project working.

## Submission Checklist

- [ ] My code runs before I submit.
- [ ] My branch name is exactly `week-03-decision-quiz`.
- [ ] My `notes.md` includes at least three required test cases.
- [ ] My pull request is open into my repo's `main` branch.
- [ ] I submitted the PR link in Canvas.

## Files

- `starter.py`: start here
- `notes.md`: include planning notes and required test cases

# Week 11: Utility Module

## Focus

imports, namespaces, and reusable helper files.

## Textbook Grounding

Official textbook: *How to Think Like a Computer Scientist: Learning with Python 3*.

- Primary reading: Chapter 12, Modules
- Main ideas: imports, namespaces, and reusable helper files
- Textbook link: <https://openbookproject.net/thinkcs/python/english3e/modules.html>

## Branch Name

Use this exact feature branch name for this assignment:

```text
week-11-utility-module
```

Open your pull request from `week-11-utility-module` into your repo's `main` branch. Submit the PR link in Canvas when this assignment is collected.

## Required Friday Project

Split a program into a main file plus a small helper module.

The goal is not to build the largest possible program. The goal is to show that you can use this week's textbook concepts correctly and explain your choices.

## Requirements I Will Check

Your program must include all of these:

- [ ] Create a helper module file such as `utils.py`.
- [ ] Define at least three helper functions in the module.
- [ ] Import the helper module into your main program.
- [ ] Call each helper function from the main program.
- [ ] Use module-name dot notation, such as `utils.function_name()`.
- [ ] Keep user interaction in the main program, not scattered through every helper.
- [ ] Print clear output showing the helper functions work.
- [ ] Include at least three test cases in `notes.md`.

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

- [ ] Add a second main program that reuses the same helper module.
- [ ] Add one more helper function to the module.
- [ ] Avoid copying helper code between files.
- [ ] Add two more test cases for the second program.

## Stretch 2: Challenge Extension

This is optional extra credit for students who already know some programming and want a more demanding version of the same week's topic.

Requirements:

- [ ] Organize related constants in the module.
- [ ] Add a small menu that calls different module functions.
- [ ] Use `if __name__ == "__main__"` appropriately in runnable files.
- [ ] Add two more test cases for menu/module behavior.

## Submission Checklist

- [ ] My code runs before I submit.
- [ ] My branch name is exactly `week-11-utility-module`.
- [ ] My `notes.md` includes at least three required test cases.
- [ ] My pull request is open into my repo's `main` branch.
- [ ] I submitted the PR link in Canvas.

## Files

- `starter.py`: start here
- `notes.md`: include planning notes and required test cases

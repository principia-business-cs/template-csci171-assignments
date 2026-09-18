# Week 12: File Tracker

## Focus

reading files, writing files, paths, and line processing.

## Textbook Grounding

Official textbook: *How to Think Like a Computer Scientist: Learning with Python 3*.

- Primary reading: Chapter 13, Files
- Main ideas: reading files, writing files, paths, and line processing
- Textbook link: <https://openbookproject.net/thinkcs/python/english3e/files.html>

## Branch Name

Use this exact feature branch name for this assignment:

```text
week-12-file-tracker
```

Open your pull request from `week-12-file-tracker` into your repo's `main` branch. Submit the PR link in Canvas when this assignment is collected.

## Required Friday Project

Read a small text file and produce a cleaned or summarized result.

The goal is not to build the largest possible program. The goal is to show that you can use this week's textbook concepts correctly and explain your choices.

## Requirements I Will Check

Your program must include all of these:

- [ ] Read from a text file using `open()` with a `with` statement.
- [ ] Process the file one line at a time or with `.readlines()`.
- [ ] Strip newline characters before displaying or counting lines.
- [ ] Count at least one useful thing, such as lines, words, or matching entries.
- [ ] Print a clear summary of the file contents.
- [ ] Use a variable for the file name instead of repeating the literal string everywhere.
- [ ] Include a small sample input file in the assignment folder.
- [ ] Include at least three test cases in `notes.md`, including an empty or very short file idea.

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

- [ ] Write the summary to a new output file.
- [ ] Include the output file name in the program output.
- [ ] Keep the required screen summary working.
- [ ] Add two more test cases for output-file behavior.

## Stretch 2: Challenge Extension

This is optional extra credit for students who already know some programming and want a more demanding version of the same week's topic.

Requirements:

- [ ] Handle a missing file with `try` / `except FileNotFoundError`.
- [ ] Let the user type the file name.
- [ ] Use a helper function for file processing.
- [ ] Add two more test cases for missing-file or alternate-file behavior.

## Submission Checklist

- [ ] My code runs before I submit.
- [ ] My branch name is exactly `week-12-file-tracker`.
- [ ] My `notes.md` includes at least three required test cases.
- [ ] My pull request is open into my repo's `main` branch.
- [ ] I submitted the PR link in Canvas.

## Files

- `starter.py`: start here
- `notes.md`: include planning notes and required test cases

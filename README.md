# Week 6 Assignment - Safe Functions

## Files

* `safe_tools.py` - Contains three safe functions for division, number conversion, and dictionary field lookup.
* `README.md` - Describes the assignment and explains why error handling is needed.

## Why can't an if check catch "abc" on its own?

An `if` check cannot catch `"abc"` during `int()` conversion because `"abc"` is text that cannot be converted into an integer, which causes a `ValueError`. The `try` and `except` blocks catch this error and allow the program to continue running instead of crashing.

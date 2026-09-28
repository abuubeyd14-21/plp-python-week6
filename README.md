PLP Python Week 6 Assignment

safe_tools.py - Contains three safe functions that handle errors using try and except.
unbreakable.py - Demonstrates handling invalid input so the program can keep running.
README.md - Contains the assignment title, file descriptions, and an explanation of error handling.

The if check cannot catch abc on its own because abc is not a number. The error happens when int() tries to convert abc into an integer, so try/except is needed to catch the ValueError.
# Week 6 Assignment — Safe Functions

- `safe_tools.py` — Provides safe division, text-to-integer conversion, and dictionary field lookup with specific exception handling, then prints the required test results.
- `README.md` — Describes the assignment files and explains why invalid numeric text must be handled with an exception.

An `if` check can inspect properties such as whether text is empty or contains only digits, but `abc` is non-empty text and still cannot be converted to an integer. Calling `int("abc")` raises a `ValueError`, so the program needs `try`/`except` to handle that conversion failure safely.

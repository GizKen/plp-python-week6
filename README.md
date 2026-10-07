PLP Python Week 6 - Safe Functions
Files
safe_tools.py - Contains three safe functions that handle division, number conversion, and dictionary lookups using try / except.
README.md - Describes the assignment and explains why an if check alone cannot handle invalid number conversion.
Why can't the if check catch abc on its own?

An if check can test a condition, but converting "abc" with int() causes a ValueError before the conversion can succeed. The try / except block catches this error and allows the program to continue running instead of crashing.
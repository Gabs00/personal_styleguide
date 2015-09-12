# My Personal Styleguide

## Purpose

To learn to write clean code and have a personal reference to clean coding guidelines.

## TOC
* [Naming](Names.md)
* [Functions](Functions.md)
* [Classes](Classes.md)

## Code Smells

* YAGNI: You aren't going to need it.
 Code only what you need now, do not code for things not needed now but that may be needed sometime in the future. It will probably not be used, or turn out to be something other than expected, thus leading to a rewrite of the code.
* DTSTTW: Do the simplest thing that works: 
 Don't get all fancy and try to be smart / super efficient. Get something working on the screen first, then refactor.
* KISS: Keep it Simple Stupid:
 The more complex, the more difficult to maintain.
* DRY: Don't Repeat Yourself:
 Don't duplicate code, turn the code into a function
* DOT: Do one thing and do it well
 Functions should do one thing, and it should do that thing well.
* One level of abstraction per Function:
 If there is more than one indent level, use the extract method to pull out code that can be made into a function
* One responsibility:
 Classes should have one responsibility, it should be responsible for that thing.
* Don't do more than one thing in functions or classes. 
 If a class seems to have too many responsibilities, make a new class. If a function does not do one thing, make more functions.
* Make functions as short as possible.

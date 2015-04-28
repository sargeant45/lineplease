# Advanced Instructions for `lineplease`

## Script Formatting
Each line should be separated by a newline. The most basic way to get Lineplease to work is with this formatting:
```
The saddest thing about that chicken crossing the road was his quick, painful death.

You know, I hear that it was not a car that killed him, but a rabid, hungry raccoon.
```
This type of formatting works, but it is very minimal. There are other ways to make your script work better with Lineplease. You can define a number for each actor playing it, and Lineplease will give each actor a different color and voice. Do that like so:
```
[1]The saddest thing about that chicken crossing the road was his quick, painful death.

[2]You know, I hear that it was not a car that killed him, but a rabid, hungry raccoon.
```
Defining a number for each actor (`[1], [2], [3], [598], etc.`) allows Lineplease to categorize the lines more formally, which will make your experience run a whole lot smoother.

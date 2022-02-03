# ruin-wordle
A fun way to completely ruin the game

https://applehat.github.io/ruin-wordle/

## Why
After discovering that wordle was a self contained app, I couldn't help but see how hard it would be to build something like this.

Turns out, it was incredibly easy

## How
Wordle just uses a array of words, and it pulls the word by index based off the current day.

In my code, this is done by calculating the unix epoch and then offsetting it by `18,797` days.

If the array inside Wordle ever changes, this app will break.

## Note
This was just done for fun.
Please don't use this to ruin other peoples fun.
Im a big fan of Wordle, and don't want to see it ruined.

### Code Quality
I made this _quickly_, and I'm not exactly proud of the code.

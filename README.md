# js-numbers-guessing-game
mdn's number guessing game.    

I created this in order to continue to use git while learning about Javascript variables
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Strings#numbers_vs._strings

Notes I took during this lesson: 
- This file has the CSS styling and the JS scripts in the HTML file, internal.
- I have separated them and moved the codes through external ways. 
- When opening the game for the first time, "We'll tell you if your guess was too high or too low." did not seem to work. 
- Since I used the Go Live feature of the "Live Server" extension, I tried opening it through the usual google-chrome and it still doesn't work.
- Therefore, I am going back to the original version xD IT WORKS. 
- I will review later on, when I gain more knowledge, the cause of this problem. 
- Game is fun :D
- Through this game, I understood converting strings to numbers. The user inputs a number, but since it was introduced in a form field, it was recognized as string. So const userGuess = Number(guessField.value); has fixed it.
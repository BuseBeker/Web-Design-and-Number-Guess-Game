# Web Design and Number Guess Game
 Web Design using React & Bootstrap
 
Instructions

1. The web site must have navigation bar specialized on web site’s topic.
2. Each component must be routed via navigation bar.
3. A slider(carousel) must exist in one of your components.
4. One of your components will contain a number guess game .

Number Guess Game

This game is based on guessing a four digit number which is composed by different numbers in each digit, such as 
1234, 8075, 6825. There is no digit repetition in the searched four digits number. 

Assume that the four digit random number is “2478”. The user will try to guess the number. The following figures are 
sample prediction cases.

If the guess is correct a “congratulations” alert will 
be appeared on the screen. 
4 digits are correct and in their correct location so 
the result will be “+4”.

If the guess is “7284”, each of the four number 
exist in “2478” but each of them are located in 
wrong place. 
So 4 numbers are guessed and each in wrong 
location.
In this case result will be -4.

If the guess is “4108”, 4 and 8 exist in “2478”. 
4 is in wrong place and 8 is located in correct place. 
So two of the numbers are guessed one of them is 
in correct place and one of them is not.
In this case result will be +1-1.

If the guess is “1408”, 4 and 8 exist in “2478”. 
Both located in correct place. So two of the 
numbers are guessed in correct place.
In this case result will be +2.

If the guess is “5109”, none of the numbers exist in 
“2478”. 
So the result must be 0.

- When the user clicks on GuessGame component on navigation bar a random 4 digit number must be generated 
composed by different numbers in each digit Such as 1234, 8075, 6825. 

- When the user clicks on “Check!” button, required javascript code must compose the correct result and print the 
result on the page.

- If the user guesses the 4 digit number correctly than a javascript alert must appear on the screen.

# Tic Tac Toe Game with JavaScript

**DEMO :** https://javascript-mini-projects-dvk.netlify.app/02-tic-tac-toe-game

Developed a responsive website for Tic Tac Toe with JavaScript where 2 users can play the game X and O who matches the pattern horizontally, vertically, or diagonally wins.

> **Technologies used:** HTML, CSS, JS, Bootstrap

# Pseudo Code

 - Get DOM elements and assign variables.
 - Get all buttons as array, filter the array that to return the text is not empty. If text is not empty length is 0 means, game logic should not execute, because all of the button values are updated. Along with that the selected current button text should be empty because non blank values should not be clicked again. Last condition should be X and O both score should be 0. If all conditions satisfy, should allow to run.
 - Get all the buttons individually and check the game pattern matches or not. If matches, execute the win function. By clicking the last element, still X or O score is zero means, then it is declared as draw.
 - Win() lets to choose winner by assign 1, trigger the popup and prints the winner message.
 - Reset the X,O to 0 and clears the button text and hide the popup.
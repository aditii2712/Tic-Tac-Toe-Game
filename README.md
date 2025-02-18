# Tic-Tac-Toe-Game
This project is a simple Tic-Tac-Toe game implemented using HTML, CSS, and JavaScript. The game allows two players to take turns marking "X" and "0" on a 3x3 grid. The game checks for a winner or a draw after each move and displays the result accordingly.

HTML Structure:-
The HTML file (index.html) sets up the basic structure of the game, including:

A heading for the game title.
A container that holds the game board with 9 boxes representing the grid.
A reset button to restart the game.
A message container to display the game result (win or draw) and a new game button.

CSS Styling:-
The CSS file (style.css) styles the game elements to ensure they are visually appealing and centered on the screen. It includes styles for the game board, boxes, buttons, and message container.

JavaScript Logic:-
The JavaScript file (app.js) contains the game logic, including:

Selecting DOM elements for the game board, buttons, and message container.
Initializing variables to track the current turn, move count, and winning patterns.
Functions to reset the game, handle a draw, disable and enable boxes, and display the winner.
An event listener for each box to handle player moves, update the game state, and check for a winner or draw.
Event listeners for the reset and new game buttons to restart the game.

This code provides a fully functional Tic-Tac-Toe game that can be played in a web browser. The game logic ensures fair play and accurately determines the game outcome.

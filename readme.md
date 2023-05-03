# Tic Tac Toe
Introduction
This is a basic Tic Tac Toe game built using HTML, CSS and JavaScript. The game allows two players to take turns adding their symbol (circle or cross) to the board. The game ends when a player has three of their symbols in a row, or when all the squares on the board are filled without a winner.

## Usage
The game can be played by opening the index.html file in a web browser. The game board will appear on the screen with an empty message area below it. The first player to go is always circle, as indicated by the message in the message area. Players take turns by clicking on an empty square on the game board. Each click adds the current player's symbol to the clicked square, and changes the current player to the other player. If a player gets three of their symbols in a row, the game ends and the message area displays the winner. If all the squares on the board are filled without a winner, the game ends in a draw.

## Files
The project consists of three files:

**index.html**: contains the HTML markup for the game board and message area
**style.css**: contains the CSS styles for the game board and symbols
**app.js**: contains the JavaScript code for the game logic


## Functions
The game logic is implemented using the following functions:

### createBoard(): 
This function creates the game board by generating a div element for each square on the board. Each square is given a unique id based on its position on the board. A click event listener is added to each square, which calls the addGo() function when clicked.

### addGo(e): 
This function is called when a square on the game board is clicked. It adds the current player's symbol (either a circle or a cross) to the clicked square, and then changes the current player to the other player. If a player has won the game, the message area is updated to display the winner. If the game ends in a draw, the message area is updated to display a draw message.

### checkScore(): 
This function checks whether a player has won the game by iterating through all possible winning combinations on the board. If a player has won, the game ends and the message area is updated to display the winner. If the game ends in a draw, the message area is updated to display a draw message.

## Styling
The game board is styled using CSS. Each square on the board is a div element with a white background color, black border, and dimensions of 100px by 100px. The symbols for each player are styled using CSS as well. The circle symbol has a blue border with a radius of 50%, while the cross symbol is rotated 45 degrees and made up of two red lines.

## Conclusion
This Tic Tac Toe game is a simple example of a game built using HTML, CSS, and JavaScript. It demonstrates the use of event listeners, conditional statements, and loops to implement game logic, and CSS styling to create a visually appealing user interface.
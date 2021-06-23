# Tic-Tac-Toe
Tic-Tac-Toe React Exercise
___

## Description
Tic-Tac-Toe as known to most people.

## Background
This project was a weekly exercise for the MITxPro coding cohort. The exercise provided experience in building an app with React.js and managing and communicating state between elements.

## Code
Basic game structure is as follows:
	< div id="root" >
	  < Game >
	    < Board >
	      < grid-row > x 3
	      	 < Square > x 3
	      < /grid-row >
	    < /Board >
	  < /Game >
	< /div >
	      	 
The <Board> manages the player (turn) and game states. The <Square>s manage the marking state. The <Board> passes a function to the <Square>s to allow them to alter state in the parent element.


## Files
The following files are contained in this repository.
1. index.html - Main document: contains 'root' element
2. tiktac2.js - contains <Game> <Board> and <Square> elements
3. superset.js - conatins logic to determine is game has been won.
4. styles.css - Stylesheet for board and game elements


# Installation
The resulting code was tested on Google Chrome. Refresh the browser to play again.

# Support
For questions contact rmc4th@yahoo.com

# Roadmap
One revision made to this package was to add logic to stop the game after a win was achieved.
Other future revision to include
1. Addition of a button to replay the game without refreshing the browser
2. Addition of logic and style to highlight the winning set of marks/squares
3. Addition of state to keep track of wins/losses/ties across multiple games.

# License Information
This work was done as part of MIT xPRO Professional Certificate in Coding. The code above comes with the following license:

MIT License

Copyright (c) 2020 John Williams

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
___


# 6-Colors-Clone
A clone of the game "6 Colors" 


1. 6 colors

2. Name:
   Or Ron 
 
   
3. Prorgam explanation: 

	This Program implement the gaem 6 colors of a human player
	playing with the computer in each turn a user can pick a color
	of the 4 colors that are not owend by him or by the computer.
	this color is used to color all his current squares and pick all the 
	sqaures that have overlap with any of his existing squares.
	After the player turnt the computer plays his turn, the computer
	is picking the color that give him the higest number of new squars.
	The winner of the game is the one which gets to more than 50% of the 
	overall board surface.

4. Design:

	there are 3 main classes:
	square - a class which holds one square not including its graphical object
	Board - a class which holds matrix of squares and which is managing the 
			logic of the game - including a recusrive funciton to search  for
			new squares to add
	ScreenPainter - a class which hold a board of all the squares and also 
		    all the grphical structures includeing a matrix of triangles
			each triangle represent one of the suares on the borad.
			ScreenPainter has a function nextStep which is called by main
			and it manages all the flow of the game.

	this program is using containers of type vector and array and it is using
	iterators to go over these containers




5. List of files:

6colors.cpp  - holds main function and nothing more			
common.h - Holds all the enums and consts for the program
ScreenPaointer.h and .cpp - hold the class which takes care of the graphics
							and the flow of the game.
board.h and .cpp - hold class board 
square.h and .cpp - hold the class square.
restart.png, kid.jpg, robot.png, Gabriola.ttf - files used but the graphics
README


6. Main data structures:
	2 matrixes - one for the sqaures in class board and one for the triangles 
	for graphical representation in the ScreenPainter class.
	1 array for the manues of colors and restart

7. Algorithms:

	Recursive algorithm to find all the squares that can be reached for
	a player from its starting point.
				 

8. known bugs - not supporting triangles - only squares.

9. comment -


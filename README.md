# Game-of-life
Game of life code in C# , first time programmer
1.	The application will implement the rules of John Conway's Game of Life using the rules described above with a Graphical User Interface to control the application and to display generations in a visual, initiative manner. 
 
2.	The size of the world will be fixed at 30 cells by 30 cells, although this must be specified using a constant so that the world size could be changed easily. 
 
It is an ABSOLUTE REQUIREMENT that a rectangular array be used to represent the grid of the world. Each element of the array will correspond to a cell of the world, with the value of the element indicating that the corresponding cell has either an “alive” creature or is empty.  
 
3.	The application will give the user the ability to  
a.	create the initial generation in a user friendly manner (typically by using the mouse and clicking on a grid to create or remove a creature). Other methods will be acceptable, but instructions must be noted in the assignment submission. Editing a text file with coordinate pairs will not be considered user friendly. 
b.	advance and display the world by a single generation,  
c.	advance the world by n generations (where n is a value input by the user) and then display the world. Intermediate generations will not be displayed. 
d.	reset the world to having no cells alive. 
e.	Select and then load a file of a specified format (see below) to set which cells are alive in the initial generation. 
f.	save the contents of the current generation in the specified format (see below) to a selected file. 
 
4.	The file format used to record coordinates will be the following: 
a.	The default extension for these coordinate files will be .gol  (Game Of Life). 
b.	The file will consist of multiple lines, with each line consisting of a pair of integers. 
c.	Each pair of integers will represent the row and column coordinates, in that order, of a cell that is alive. Each value in the pair will be separated by one or more blanks, tab characters or commas. The coordinates will be zero origin; a coordinate pair of (0,0) will be the top left corner of the world. 
d.	Blanks lines will be ignored. 
 
5.	When a new generation is determined, if no cells were born and no alive cells died then the word has reached a stable state. When this happens, no further changes ever can occur. This situation must be detected, an appropriate message displayed to the user, and the ability of the user to advance the generation(s) should be disabled. 

John Conway devised a new game in 1970 called the Game of Life. It is a celluar automation simulator.

Life and Death in the game follow the four basic rules:
Any live cell with fewer than two live neighbours dies, as if caused by under-population.
Any live cell with two or three live neighbours lives on to the next generation.
Any live cell with more than three live neighbours dies, as if by overcrowding.
Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

My goal is to recreate the game in C and continually improve the code by learning new aspects of the language
and programming in general. 

COMPILE NOTES:
Currently written for the MS Visual C++ 2010 compiler. I am working on moving the next version to Linux.

For Linux compilation, remove the following:
#include "stdafx"

Cheers,
Vulcant
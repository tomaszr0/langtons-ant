# Langton's ant
Langton's ant is a simple cellular automaton tracking movement of ants on two-dimensional grid of cells. These cells can have a certain amount of states usually represented with colors.

Rules:
- every iteration ant will turn depending on the state of the cell it's standing on; if cell's state is even, ant will turn right, otherwise will turn left; cell's state will then increment and, if exceeded limit, return to initial value; after this ant will move forward; this process will repeat for each ant
- grid will expand each time an ant attempts to go beyond current borders
- ants do not interact with each other directly
- multiple ants can exist on the same cell

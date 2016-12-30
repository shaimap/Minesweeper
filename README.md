# Minesweeper

BASIC GAME DESCRIPTION:

This is a classic minesweeper game in which the object of the game is to clear the board without setting off any of the mines. The game is 15x16 grid of minesweeper squares.

INSTRUCTIONS:

Press new game to start a new random game.
If you press a grid square that itself is a mine, the game will end. The mine triggered will be displayed in red, and the rest of mines on the game board will be displayed as well.
If you press a grid square that itself is not a mine, but has mines surrounding it, surrounding squares will display the number of mines that surround themselves.
If you press a grid square whose adjacent squares have no mines surrounding them, you will recursively uncover those squares as well, until the patch of grid squares have at least one mine surrounding them.

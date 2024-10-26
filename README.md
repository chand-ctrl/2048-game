# 2048-game
The 2048 game is a sliding puzzle game where the objective is to combine numbered tiles on a grid to create a tile with the number 2048.

Here are the key rules:

Grid Layout: The game is played on a 4x4 grid (16 cells).

Tile Values: The tiles on the grid are numbered as powers of 2 (2, 4, 8, 16, 32, etc.).

Objective: Combine tiles to reach the 2048 tile. The game can continue after reaching 2048 to get higher numbers, but the challenge is to achieve 2048.

Tile Movement:

You move all tiles on the grid by swiping up, down, left, or right.
All tiles slide in the direction you swipe until they hit another tile or the edge of the grid.
If two tiles of the same number collide during a move, they merge into a new tile with the sum of their values (e.g., two 2s merge into a 4, two 4s into an 8, etc.).
Spawning New Tiles: After each move, a new tile with a value of either 2 or 4 appears in a random empty spot on the grid.

Game Over: The game ends when there are no empty spaces and no possible moves left (i.e., no adjacent tiles can be combined).

Winning Condition: The game is "won" when you successfully create a tile with the value 2048.

Scoring: The score is based on the value of tiles combined during each move. The higher the values, the more points you earn.

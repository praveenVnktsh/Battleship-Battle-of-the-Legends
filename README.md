# Battleship - Battle of the Legends

Made this game for Project ISAAC, during the Coronavirus Pandemic of 2020.

### Rules

Rules for the game are simple:
1) Place your ship on the grid in whatever orientation you want on the 10x10 board.
2) Press any key  (or space) to rotate your selected ship.
3) Press F1 to begin the game.
4) The goal of the game is to sink all of the computer's ships.
5) Press on the tile of your choice to make your attack.
6) Sink all of the enemy ships before the computer sinks yours.

### Computer AI

The AI uses the following policy to make decisions on where to hit:
1) Shoot random tiles until a hit is achieved.
2) Once a tile is determined to be a hit on a ship, find the orientation in which the ship is placed by hitting the tiles around it.
3) Once the orientation is determined, destroy the ship until the ship is sunk.
4) Repeat from step 1.

### TODO

1) Experiment with Reinforcement Learning to determine if victor can be achieved faster than human-like-policy.

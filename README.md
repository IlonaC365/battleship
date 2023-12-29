This is the Battleship project General idea Battleship is usually a two-player game, where each player has a fleet of ships and an ocean where the ships are placed, 
but hidden from the other player, and both players compete to sink the other player's fleet first. 
You need to implement a variation of this game: only the computer player has its Fleet and arranges the ships, while the human player attempts to sink them.
The Ocean is the field of Battleship game. It is a rectangle (matrix) of square cells, which consists of M rows and N columns of cells.
Each ship of the Fleet might be of one of the following ship types, which differ with the number of vertically or horizontally adjacent Ocean cells in a line they occupy:

Carrier (5 cells); Battleship (4 cells); Cruiser (3 cells); Destroyer (2 cell); Submarine (1 cell).

"C:\Users\ilonk\OneDrive\Pictures\Screenshots\Screenshot 2023-12-29 160337.png"


How to win Each player has a battlefield represented by a 10x10 grid (default) on which he places 5 ships, hidden from his opponent. 
The goal of the game is to sink all the opposing ships! A ship is sunk when it is hit once for each space it occupies. 
In other words, a submarine, which occupies two spaces, is sunk after being hit twice. The 5 ships occupy 15 total spaces, so the first player to record 15 hits wins!

Place your ships To place a ship you need to enter a departure coordinate (A1-J10 for the default 10x10 board) and a direction (vertical or horizontal). 
For example: "A1" and 'H' or "B7" and 'V'. Shoot the enemy ships Once both players have configured their ships, the battle may have started!

Shoot the Enemy Ships: Shoot your opponent’s ships by matching the coordinates. You will be informed if you have hit or missed a ship.
A ship is sunk after being hit once for each space it occupies. Sink all 5 computer ships to win!

Technologies:
Java

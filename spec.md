# Minesweeper

Note: every information defined here, sourced from minesweeper wiki, which can be found in http://www.minesweeper.info/wiki/Windows_Minesweeper.

## How to Play

Simply click on cells available in playground. There are several mines scatered randomly across the plane, which hidden inside the cell. On left clicking the cell, there's 2 probabilities:

1. on clicking cell which doesn't contains hidden mine, player will reveal adjacent (recuresively) cell content which hides no mine. Cells will also reveal number (`1`, `2`, or `3`) which indicates number of mines hidden in 3x3 cells adjacent to the numbered cells.
2. on clicking cell which contains hidden mine, every mine in the plane will be revealed and the game will be over.

On right clicking, you can place/remove flag which is a sign for mined cell. Flags have limited number according to which level you are playing (`beginner`, `intermediate`, or `expert`).

## Levels

1. **Beginner**
   8 x 8 plane, 10 mines.
2. **Intermediate**
   16 x 16 plane, 40 mines.
3. **Expert**
   24 x 24 plane, 99 mines.

_Number of flags available determined by number of mines._

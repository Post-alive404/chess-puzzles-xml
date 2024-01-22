# Spring Chess Puzzles XML

Chess is a famous table game. 

## Details

### State String Symbols:

|Symbols|Meaning|
|---|---| 
| . | empty cell|
| K | black king|
| Q | black queen|
| R | black rook, castle|
| B | black bishop|
| N | black knight|
| P | black pawn|
| k | white king|
| q | white queen|
| r | white rook, castle|
| b | white bishop|
| n | white knight|
| p | white pawn|

Example:
```
RNBQKBNR
PPPPPPPP
........
........
....p...
........
pppp.ppp
rnbqkbnr
```

### Cell address
To address a cell, we use a regular chess scheme, as in an example below:
```
8│RNBQKBNR
7│PPPPPPPP
6│........
5│........
4│....p...
3│........
2│pppp.ppp
1│rnbqkbnr
 └────────
  ABCDEFGH      
```

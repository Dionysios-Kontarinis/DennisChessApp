NumberSliding
===============

This is a game based on a well-known number sliding puzzle. By running "NumberPuzzleApp.class":

* The user is requested to create a square with 9 elements.
* Each element is a number in [1,9] except from 3. Also, one element is "void".
* The user can choose:

1. To play the game himself. In this case, he is asked to play a series of moves (one move slides an element to its adjacent "void")
until he properly arranges all 9 elements (1 2 "void" # 4 5 6 # 7 8 9).

2. To ask the help of our engine. If the engine sees a series of moves leading to the desired arrangement, then it will play them instantly,
one-by-one. Otherwise, it will use a heuristic in order to play a single "good" move, and it will continue from there.

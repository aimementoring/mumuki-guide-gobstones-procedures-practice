This time, the activity is quite simple: create a procedure RedToTheEdge which drops a red stone in the top left corner of the board.

**Watch out**: _The position of the head and the size of the board are unknown. As a consequence, you can't use `Move` in order to get to the corner._

There is a primitive (:gift:) called `GoToEdge`, which takes a direction and moves in that direction to its limit, **up to the edge**. In this case, your goal is to place the head in a corner, so you need to think of two edges: North and West.

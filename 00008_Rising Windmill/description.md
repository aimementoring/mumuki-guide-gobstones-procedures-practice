Well, now let's do an exercise to think a little bit…

The idea is to create a program which makes a “windmill” as the one shown in the picture.
It's supposed that the head is already in the center of the board.
Pay attention that in every “blade”, the number of stones increases as long as the head moves away from the center.

<gs-board>
  GBB/1.0
    size 7 7
    cell 3 0 Negro 3
    cell 3 1 Negro 2
    cell 3 2 Negro 1
    cell 3 4 Negro 1
    cell 3 5 Negro 2
    cell 3 6 Negro 3
    cell 0 3 Negro 3
    cell 1 3 Negro 2
    cell 2 3 Negro 1
    cell 4 3 Negro 1
    cell 5 3 Negro 2
    cell 6 3 Negro 3
    head 3 3
</gs-board>

The key point here is to think **which part is repeated**, and then define the strategy.
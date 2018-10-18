Let's see a reloaded version of `DropPoints3` which, clearly, will be called `DropPoints3Reloaded`.

What's the difference? Now it must drop 1 stone, then 2 and finally 3; watch out!: you must **strictly** respect the number of stones we asked, otherwise, your procedure will fail.

As one picture is worth a thousand words, down here is an example of how the board must look like after executing `DropPoints3Reloaded(Green)`, beginning from the indicated cell:

<gs-board>
  GBB/1.0
    size 7 2
    cell 0 1 Verde 1
    cell 3 1 Verde 2
    cell 6 1 Verde 3
    head 0 1
</gs-board>

This time, we don't mind the position of the head.
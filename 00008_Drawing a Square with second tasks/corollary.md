Have you realized the importance that `DrawBlackLine3` left the head in the current cell?
This is the magic of dividing in second tasks: one problem is dealt with at the time, and then we only need to combine the small tasks in order to achieve our goal.
In addition, the code is much clearer (it is less complicated to understand what it does), shorter (it is easier to read) and communicates the chosen strategy we thought to solve the problem, in a better way.

Compare your version with the one we had done at the beginning, and you will see we are not lying:

```gobstones
procedure DrawBlackSquare3() {
  Drop(Black)
  Move(East)
  Drop(Black)
  Move(East)
  Drop(Black)
  Move(North)
  Drop(Black)
  Move(West)
  Drop(Black)
  Move(West)
  Drop(Black)
  Move(North)
  Drop(Black)
  Move(East)
  Drop(Black)
  Move(East)
  Drop(Black)
}
```

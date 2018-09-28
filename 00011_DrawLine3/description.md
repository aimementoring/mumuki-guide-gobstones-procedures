Now it's your turn!

Basing on DrawBlackLine3…

```gobstones
procedure DrawBlackLine3() {
    Drop(Black)
    Move(East)
    Drop(Black)
    Move(East)
    Drop(Black)
    ComeBack()
}
```

…write a procedure `DrawLine3` which gets a color and draws the line in that color.

We will be in charge of writing the `program`s to use it with every one of the colors.
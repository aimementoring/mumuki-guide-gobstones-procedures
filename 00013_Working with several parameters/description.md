As we explained in the previous exercise, procedures may have more than one **parameter** (or _small hole_). For instance, what would happen if we wanted DrawLine3 to draw lines in any direction?

Undoubtedly, we will need the user of the procedure to tell us, apart from the “color”, which “direction” he/she wants the line to be drawn; and for that we need a **new parameter**. And how do we do this?

Very easy, just like we do when writing, we will **separate every parameter using commas**.

Look how it is:

```gobstones
procedure DrawLine3(color, direction) {
  Drop(color)
  Move(direction)
  Drop(color)
  Move(direction)
  Drop(color)
}
```

(In order to simplify the explanation, we will set aside the final position of the head for now. We will come back to that later on.)

> Your job now is to write a program which uses the new version of `DrawLine3` (you don't need to create it, only use it) and draw a multicolored square like this one:

<gs-board>
  GBB/1.0
    size 4 4
    cell 0 1 Azul 1
    cell 0 2 Azul 1
    cell 0 3 Azul 1
    cell 1 3 Negro 1
    cell 2 3 Negro 1
    cell 3 3 Negro 1
    cell 3 2 Rojo 1
    cell 3 1 Rojo 1
    cell 3 0 Rojo 1
    cell 2 0 Verde 1
    cell 1 0 Verde 1
    cell 0 0 Verde 1
    head 0 0
</gs-board>

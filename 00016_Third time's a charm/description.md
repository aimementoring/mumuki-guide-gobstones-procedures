In order to finish with multiple parameters, we will ask you to work with a procedure…with three parameters!

What this procedure, called `Triad`, must do is simple: drop three stones, one at the side of the other to the East, and matching the color with the parameter.

The head begins in the origin and must end on the last stone of the Triad.
For example `Triad(Red, Blue, Green)` would result in this:

<gs-board>
  GBB/1.0
    size 3 1
    cell 0 0 Rojo 1
    cell 1 0 Azul 1
    cell 2 0 Verde 1
    head 2 0
</gs-board>

while `Triad(Blue, Green, Red)` would do this:

<gs-board>
  GBB/1.0
    size 3 1
    cell 0 0 Azul 1
    cell 1 0 Verde 1
    cell 2 0 Rojo 1
    head 2 0
</gs-board>

> Try the procedure `Triad`, which has to use 3 parameters.
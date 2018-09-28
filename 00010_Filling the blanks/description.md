Let's understand what we've just done
The first thing we did was to declare a procedure, but with a little difference: it takes a parameter, called “color”.

```gobstones
procedure Drop3(color) {
  Drop(color)
  Drop(color)
  Drop(color)
}
```
Parameters (those names between brackets) are special, since they are replaced by real values when we invoke them. For example, if they are invoked like this…

```gobstones
program {
  Drop3(Black)
}
```

…what is executed is:

```gobstones
Drop(Black)
Drop(Black)
Drop(Black)
```

And if they are invoked like this…

```gobstones
program {
  Drop3(Red)
}
```

…what is executed is

```gobstones
Drop(Red)
Drop(Red)
Drop(Red)
```

Note that every time “color” appears, it is replaced by the value written in the invoking.

> Let's see what can be done so far: write a program which drops three green stones using the procedure Drop3.

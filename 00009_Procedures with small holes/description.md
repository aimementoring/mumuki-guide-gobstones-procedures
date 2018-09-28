What if I want to do a red square now? Or a green one?
Do I have to write everything again? Of course **not**!

Programming is about automating repetitive tasks! :smile:

Let's start with something easy: suppose we want to **generalize** the procedure `Drop3Green`, in order for it to work with any color we wish (but only one at the time).
What we need is to add the procedure a kind of _hole_…

```gobstones
procedure Drop3(color) {
  Drop(color)
  Drop(color)
  Drop(color)
}
```

…that can later be completed any time it is used:

```gobstones
program {
  Drop3(Black)
  Drop3(Red)
}
```

> Write the previous codes in the editor and check what happens.
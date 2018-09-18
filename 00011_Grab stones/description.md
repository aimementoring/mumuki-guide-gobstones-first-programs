In the same way that there is a “drop a stone” (Drop), there is a “grab a stone” (Grab), which removes exactly one stone of the given color.

For example, the following program grabs two stones of the initial position.

```gobstones
program {
  Grab(Red)
  Grab(Red)
}
```

> Knowing this, write a program which removes only the small red ball of this board. Watch out! Pay attention to the position of the head. : wink:

<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>

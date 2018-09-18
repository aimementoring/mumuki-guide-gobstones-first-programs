Great! You have already understood how to move the board head using the operation Move and the directions (South, West, etc). Let's go a step further: **the stones**.

In any cell of our board we can drop `stones`. They have different colors:

* Red 
* Blue 
* Black 
* And Green 

For example, this is a board with a red stone and a black stone:

<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>

Apart from moving, the head also can drop stones in the **current cell**. For that, we have the operation `Drop`, which orders the head to insert a stone of the given color.

```gobstones
program {
  Drop(Red)    
}
```

> Try this program! Write the code in the editor, send it and you will see what happens when executing it on this board:

<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>
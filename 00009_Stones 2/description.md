Something interesting of our boards is that in their cells, we can drop any number of stones of any color.
 
For example, if we have this board:

<gs-board>
  GBB/1.0
    size 5 2
    head 3 1
</gs-board>
 
and we execute the following program:

```gobstones
program {
  Drop(Red)
  Drop(Red)
  Drop(Blue)
  Drop(Green)
  Drop(Red)
}
```
the head will insert in the current cell three red stones, a blue one and a green one.
 
> Write this program in the editor and check how it appears in the board!

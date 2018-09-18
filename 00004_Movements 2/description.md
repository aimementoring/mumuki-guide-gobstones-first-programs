Let's understand what we just did: write a program.

Every program has exactly one program: a section of the code which declares the commands (actions) that we want the computer to execute on the initial board. By executing a program, we get a final board.

The syntax of a `program` is really simple:

1. we write a line which says `program`, followed by an opening key: `{`

2. next, the commands: one per line

3. and finally, one last key which closes the one we used before `}`

Some examples of `program`s:

```gobstones
program {
}
```

(makes nothing)

```gobstones
program {
  Move(North)
}
```

(moves the head one position to the north)

```gobstones
program {
  Move(North)
  Move(North)
}
```

(moves the head two positions to the north)
 
> Knowing this, write a program which, on a 2x4 board with the head in the initial point (the left bottom cell), moves the head three times to the north.

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 2 4
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 2 4
        head 0 3
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>
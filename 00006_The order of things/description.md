When working with Gobstones, things are done following certain order.
For example, if we have this program:
 
```gobstones
program {
  Move(North)
  Move(East)
}
```

a simple way to read it (called **operational**) is the way a computer would do it, in order, from top to bottom:
first, it moves to the north:
Move(North)
then, it moves to the east:
Move(East)
And, in fact, it is executed in this way. This _how_ it does it.
 
However, human beings, usually think according to the final result, that is to say, we give importance to the **objective** of the program. We prioritize _what_ it does than how it does it. This **denotative** way leads us to say that, simply, the head is moved to the northeast.

That is why there are many ways to solve a same problem: we can write different programs that do the same thing (what), but that do it in a different way (how).

> Let's see if you get this: write another program which does the same thing than the previous one (move to the northeast), but in a different way. Watch out: it has to work in a 2x2 board.

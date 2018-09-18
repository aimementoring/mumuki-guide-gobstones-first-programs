Note that this two programs make the same thing:

```gobstones
program {
  Move(East)
  Move(East)
  Move(South)
}
```

```gobstones
program {
  Mover(East)
  Mover(South)
  Mover(East)
}
```
Moral: as we told you in the beginning: There isn't an unique way to solve a problem! In addition, sometimes, the order is not so important. Come with us to understand this in a better way.

Note that in this problem, if we change the order in which we called (use) Drop, the result doesn't change: there always will be a board with three red, one blue and one green red stones.
 
For example, the following two programs also solve this same problem:

```gobstones
program {
  Drop(Red)
  Drop(Red)
  Drop(Red)
  Drop(Green)
  Drop(Blue)
}
```

```gobstones
program {
  Drop(Red)
  Drop(Blue)
  Drop(Red)
  Drop(Green)
  Drop(Red)
}
```
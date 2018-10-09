As you noted in the previous exercise, the generated board had a marked **cell**:
 
<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board> 


Why is that? Because our computer has a **head**, which is always situated upon one of the board cells, and can execute different operations on it (be patient, we will get to know them).
 
For example, look at the following 5x2 board with the head situated on the second row and fourth column.

<gs-board>
  GBB/1.0
    size 5 2
    head 3 1
</gs-board>
 
One important thing: we count rows from the bottom up, and columns from left to right.
 
The first **row** is the one of the bottom, and the first **column** is the one of the left.

> Still have doubts? Press “send” and we will generate a 3x3 board with the head on the second column and third row.

Up to this point, what you did wasn't much exciting, was it? That is because we haven't taught you yet how to give the computer instructions, and we have only showed you a board.
 
In this exercise we will learn one of the instructions we can give to the computer: to move the head.
For instance, starting from an **initial** empty board, we can easily write a program that moves the head one position to the **north**.

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
        size 3 3
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        head 0 1
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>
 
The program **code** (meaning the **text** of the description of the solution we will give the computer) that achieves this is the following:

```gobstones
program {
  Move(North)
}
```
 
> Don't you believe us? Write down the previous code in the editor and press “Send”.
As you can imagine, not only the head can be moved to the north, and a program can combine any kind of movements.
Write a program which moves the head two positions to the East and one to the South, resulting in the following effect:

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
        head 0 2
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        head 2 1
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>
 
Remember that the command which moves the head is called Move (neither mOvE or move or MOVE).
 
Observe the syntax is very important!
 
If you don't do it, the program won't work.

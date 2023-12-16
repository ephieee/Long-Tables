# Long-Tables

There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content).These elements help people 
who use screen readers and also allow you to style these sections in a different manner than the rest of the table (as you will see when you learn about CSS).
<thead>
The headings of the table should sit inside the <thead> element. 
<tbody>
The body should sit inside the <tbody> element. 
<tfoot>
The footer belongs inside the <tfoot> element.

<table>
 <thead>
  <tr>
   <th>Date</th>
   <th>Income</th>
   <th>Expenditure</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <th>1st January</th>
   <td>250</td>
   <td>36</td>
  </tr>
  <tr>
   <th>2nd January</th>
   <td>285</td>
   <td>48</td>
  </tr>
  <!-- additional rows as above -->
  <tr>
   <th>31st January</th>
   <td>129</td>
   <td>64</td>
  </tr>
 </tbody>
 <tfoot>
  <tr>
   <td></td>
   <td>7824</td>
   <td>1241</td>
  </tr>
 </tfoot>
</table>

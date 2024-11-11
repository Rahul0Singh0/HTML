# table : 
In HTML, a <table> element is used to create a table for organizing and displaying data in a structured, grid format. Here are the basic tags associated with an HTML table and their uses:

## table and its attributes:
<table>: Defines the start and end of the table.
 border : Specifies the width of the border around the table and its cells.
 cellpadding: Sets the space between the cell content and the cell border.
 cellspacing: Sets the space between individual table cells.
Example: <table> ... </table>

<tr> (Table Row): Defines a row in the table.
Example: <tr> ... </tr>

<th> (Table Header): Specifies a header cell in the table. The content inside <th> is bold and centered by default.
Example: <th>Header</th>

<td> (Table Data): Defines a cell of data within a row. Cells with <td> are typically left-aligned.
Example: <td>Data</td>

## note:
  colspan="3": Merges the cell across 3 columns.
  rowspan="3": Merges the cell across 3 rows.

<thead>: Groups the header content in the table. Useful for styling and for making the header section distinct from the body.
Example: <thead> <tr> <th>Header</th> </tr> </thead>

<tbody>: Groups the body content of the table, making it easier to style or manage large tables.
Example: <tbody> <tr> <td>Data</td> </tr> </tbody>

<tfoot>: Groups footer content. Usually for summary or final values.
Example: <tfoot> <tr> <td>Footer Data</td> </tr> </tfoot>

<caption>: Adds a title or description for the table.
Example: <caption>Table Title</caption>
# Tables

A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results

Each block in the grid is referred to as a table cell. In HTML a table is written out row by row.

## Basic Table Structure

* `<table>`

    The `<table>` element is used to create a table. The contents of the table are written out row by row.

* `<tr>`

    You indicate the start of each row using the opening `<tr>` tag. (The tr stands for table row.)

* `<td>` 

    Each cell of a table is represented using a `<td>` element. (The td stands for table data.) At the end of each cell you use a closing `</td>` tag.


* `<th>`

    its purpose is to represent the heading for either a column or a row. (The th stands for table heading.) 

* `<tr>`

   it uses the rowspan attribute to stretch down and take over the cell below.    

* For long tables you can split the table into a `<thead>, <tbody>, and <tfoot>`

            <table>
            <tr>
            <th></th>
            <th>ABC</th>
            <th>BBC</th>
            <th>CNN</th>
            </tr>
            <tr>
            <th>6pm - 7pm</th>
            <td rowspan="2">Movie</td>
            <td>Comedy</td>
            <td>News</td>
            </tr>
            <tr>
            <th>7pm - 8pm</th>
            <td>Sport</td>
            <td>Current Affairs</td>
            </tr>
            </table>


            
 <br>

### [Back](https://raghadmustafa96.github.io/reading-notes/README-7)
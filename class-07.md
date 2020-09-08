# reading notes class 7

## domain modeling

- domain modeling is the process of creating a conceptual model in code for a specific problem.
- define a constructor and initialize properties.
- you have to define the same properties between many objects.
- a constructor function is defined using a function expression.

- the `new` keyword creates an object.
- the constructor function creates properties inside that object using the `this` variable
- the object is stored in a variable for later use.

`math.random()` generates random numbers.

## Tables

- a tabel represents information in grid format. 
- each block in the grid is refered to as a table cell.
- `<table>` - used to create a table
- `<tr>` the start of each row.
- `<td>` each cell of a table.
- `<th>` table headings

- ex.. 

- `<table>`
-    `<tr>` row
        `<th>`heading`<th>`
                `<td>`cell`</td>`
       `<td>`cell`</td>`
-    `</tr>`
- `</table>`    

- `colspan` indicates how many columns a cell should cross. *left-right*
- `rowspan` how many rows a cell should cross. *up-down*

- ## constructing an object
- the `new` keyword and the object constructor create a blank object. you can add properties and methods to the object.

- to create an empty objects use `var name = {}`

- `this` is a keyword. it is used to refer to the properties of an object *within* the object, its functions, and methods.

- arrays are objects that use index numbers instead of properties.
- you can use arrays in objects, and objects in arrays.

- an **object model** is a group of objects that represents  related things from the real world. 

- **there are bulit in objects.**
- browser object model represent current window or tab.
- document object model uses objects to create representation of the current page.
- global javascript objects represents things that the JS language needs to create a model of.




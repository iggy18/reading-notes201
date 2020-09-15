# charts

- charts are used for displaying data visually. 

- drawing a line chart
- first create a canvas element 
- `<canvas id="buyers" width="600" height="400"></canvas>`

- next write a script to retrieve the canvas element
- `<script>`
-  `var buyers = document.getElementById('buyers').getContext('2d');`
-  `new Chart(buyers).Line(buyerData);`
- `</script>`

- drawing a pie chart
- `var placeholder1= document.getElementById("elementName").getContext("2d");`
- `new Chart(placeholdler1).Pie(pieData, pieOptions);`

- drawing a bar chart
- `var placeholder1 = document.getElementById("elementName").getContext("2d");`
- `new Chart(placeholder1).Bar(barData);`

- the canvas element
- <canvas id="bigly" width="400" height="365"></canvas>

- `fillRect(x, y, width, height)`
- Draws a filled rectangle.

- `strokeRect(x, y, width, height)`
- Draws a rectangular outline.

- clearRect(x, y, width, height)
- clears the area and makes the rectangle fully transparent.

- drawing text using fillStyle
- function draw() {
-  var ctx = document.getElementById('canvas').getContext('2d');
-  ctx.font = '48px serif';
-  ctx.fillText('Hello world', 10, 50);
}

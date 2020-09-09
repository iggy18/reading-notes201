# Layout.


- if a block level element sits inside another block level element then the outer box is know as the **parent**.
- **position:** *reletive* moves an elemet from where it would be in normal flow.
- **position:** *absolute* positions element in relation to its parent.
- **position:** *fixed* positions element in relation to browser window.
- *float* allows you to to position element to far left or right.
- float can place elements side by side.
- the **clear** property says that no element should touch the left or right hand sides of a box.

### creating multi column layouts
1. create a `<div>` element to represent each column
2. `width` sets the width of the colums
3. `float` positions the colums next to each other
4. `margin` creates a gap between the columns.  

- different users will have different sized screens.
- most designers create pages around 960-1000 pixels wide because most users will be able to see a site this wide on thier screen.
- *fixed width* layouts do not change size with browser window. this is done in pixels
- *liquid layouts* stretch and contract as user changes browser size. this is done in percentages.
- grid layouts help a designer copose the elements of a website.
- CSS - frameworks make like easier by providing the code for common tasks.
- there can be multiple CSS files linked to one page.

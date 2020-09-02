# Reading 3

## Lists
- HTML provides three diferent lists.
1. Ordered.
2. unordered.
3. definition lists - a set of terms and definitions.

- `<ol>` - ordered list.
- `<li>` - list item.
- `<ul>` - unordered list.
- `<dl>` - definition list.
- `<dt>` - definition term, to be defined.
- `<dd>` - the definition.

## Boxes

- **box demensions - width, height.**
- boxes can be measured by pixels, percentages, or ems.
- pixels allow for accurate control of size.
- percentages make the size of the box reletive to the size of the browser window. 
- ems size of the box is based on the text within.

**limiting width**
- min width, max width.
- indicates how wide a box can get when the viewing window is stretched around.
- limiting height - min height, max height - indicates how high a box can get when window is stretched around. 
- overflow - what the browser can do if the content within a box is larger that the box itself.
1. hidden - hides extra content
2. scroll - adds a scroll bar so you can scroll to see the extra content.

- border - seperates the edge of one box from another.
- margin - the space outside the border
- padding - space between the border and the content within

**border width**
- thin, thick, medium. can be sized in pixels as well.
- you can control the width of individual sides. `border-top-width`or `border-right-width`, or by specifying four px sizes in clockwise order `border-width: 1px 2px 3px 4px;`
- you can specify broder styles from solid, to dashed, to dotted, to hidden, etc...
- you can also specify a color for the border
- border shorthand can combine these properties. `border: 4px solid red;`

**padding** 
- adjusted with `padding-top` or `padding-left`, also has shorthand `pading: 10px 15px 10px 15px;`

**margin**
- adjusted with `margin-left` or `margin-bottom` also has shorthand.

**centering** 
- you must firt specify the width of the box.
- setting left and right margins to auto will center the box.

**change inline/block**
- inline - causes block element to act like inline element.
- block - causes inline element to act like block element.
- inline-block - causes block level element to flow like an inline element while retaining other features of a block.
- none - hides an element from the page.

**hiding boxes**
- hides boxes from users but leaves a space where the boz should have been.
1. `visibility: hidden;` - hides element
2. `visibility: visible;` - shows element

**border image**
- applies image to the border of any box

**box shadows**
- allows you to add drop shadow to any box.

**border radius**
you can round the corners with `border-radius: 10px 10px 10px 10px;`
to make elipticle shapes target two sides.

## Decision and Loops
-using **if else** statements allow you to provide two sets of code
1. *if* true - choose this path
2. *else* false - choose this path

**switch statements**
- indicates a possible value for a variable and the code that should run if the variable matches that value.
- use `break;` to make sure the rest of the code doesn't run.

**loops**
- loops check a condition, if it returns true a code block will run, and it will be checked again and again until it is returned false.

- 3 main types.

1. for - run a specific number of times.
2. while - if you do not know how many time it should run, but need a certain answer.
3. do while - similar to the while but will always run the statements inside curly braces at least once, even if false.
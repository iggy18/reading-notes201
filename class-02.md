# class 02 reading

## Text
- when creating a web page, you add tags to the contents of the page. those tags tell the browser what the loyout of the page should look like.
- heading tags are used to increase the size of the font. H1 is the largest and it goes down from there.
`<h1>` `<h2>` `<h3>` `<h4>` `<h5>` `<h6>`
`<p>` paragraph tags go around a pargraph.
`<b>` bold.
`<i>` italic.
`<sup>` superscript is raised text like when you use a power in math.
`<sub>` subscript is lowered like in H2O.
`<br />` line break.
`<hr />`horizontal rule adds a line between sections.

## Semantic Markup
- text elements do not affect the structure of a page, but do add extra information.
`<strong>` important content that displays in bold font.
`<em>` shows emphasis, displays as italic.
`<blockquote>` used for longer quotes that take up a pargraph.
`<q>` for shorter quotes to sit within a paragraph.
`<abbr>` used for abbreviations and acronyms, displays an attribute with explaination.
`<cite>` refrencing a source. displays as italic.
`<dfn>` defineing an instance.
`<address>` used to contain contact details. often displayed as italic.
`<ins>` inserted text is underlined.
`<del>` deleted text is scratched out.
`<s>` also scratched out when no longer relevant.

## Introducing CSS
- imagine there is a box around every HTML element. CSS allows you to customize those boxes.
- a CSS style rule contains two parts a **selector** and a **declaration**
- *selectors* indicate which element the rule applies to.
- *declarations* indicate how the elements refered to should be styled. 
- a declaration is made of two parts the **property** and the **value**.
- *property* aspect of the element that you want to change ex... font-family
- *value* specify the settings you want to use. ex... font family: *comic sans*;

- you can use an external CSS file by `<link>`ing it in the head of an HTML doc. 
- you ucan also use CSS rules inside of an HTML page by using the `<style>``</style>` tags.

CSS selectors

`* {}`  universal selector.
`h1 {}` type selector.
`. {}` class selector.
`# {}`ID selector.
`this>thenThis {}`child selector.
`this thenThis {}`descendant selector.
`this+thistoo`adjacent sibling selector.
`this~thenThis`general sibling selector.

## Basic Javascript Instructions
- a **statement** is each individual step in in a **script**
- **comments** explain what your code does. coomments are made with `//` multiline comments are `/* */`
- a variable `var` is where a script will temoprarily store bits of information.
- **three data types.**
1. numeric - numbers.
2. string - letters and other data.
3. boolean - true or false.

**six rules for naming variables**
1. name must begin with a letter, a dollar sign $, or an underscore. it must not start with a number.
2. name can contain letters $ or _. do not use a dash - or a period in a variable name.
3. cant use keywords or reserved words.
4. variables are case sensitive. it is bad practice to use "no" and "No".
5. use a name that describes the kind of info the variable stores.
6. if your variable has more than one word capitolizeTheBeginningOfEveryOtherWord. you can also use an _.

- an **array** stores a *list* of values `[4,5,6,7]`
- values in arrays are accessed like they are in a numbered list. numbering always starts at *zero*, not one.

- **expressions** evaluate into a single value.
- **operators** allow programers to create a single value from one or more values
 
**arithmetic operators**
arithmic operators use numbers 
`+, -, /, *,` - add, subtract, divide, multiply
`++` increment - adds one to current number 
`--` decrement - subtracts one from current number
`%` modulous - divides two values and returns remainder

*need to know the order of execution*

string operators - the `+` symbol is the only string operator. it is used to join string on either side of it.

## Decisions and loops
- there are often several places where decisions are made that determine which lines of code should be run next. flowcharts can help you plan for these occasions
- there are two componants to a decision:
1. expression is evaluated, which returns a value
2. a conditional statement says what to do in a given situation

**comparison operators**
`==` equal to
`!=` not equal to
`===` strict equal to
`!==` strict not equal to
`>` greater than
`<` less than
`>=` greater than or equal to
`<=` less than or equal to

**logical operators**

`&&` logical and - tests more than one condition.
`||` logical or - at least one condition.
`!` logical not - inverts a single boolean value.

**if statments**
checks a condition,. if true, statement in subsequent code block are executed.

**if...else statements**
if it is true the first block of code is executed, if flase the second block runs instead.
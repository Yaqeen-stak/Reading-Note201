# HTML 
## Links :
HTML links are hyperlinks,You can click on a link and jump to another document.
When you move the mouse over a link, the mouse arrow will turn into a little hand.
Links are created using the `<a>` element. Users can click on anything
between the opening `<a>` tag and the closing `</a>` tag. You specify.

**Relative URLs**
You can use relative URLs which are a shorthand way to tell the browser where a page is in
relation to the current page.

**Email Links**
`mailto:`
HTML `<a>` tag provides you option to specify an email address to send an email. While using `<a>` tag as an email tag, you will use mailto: email address along with href attribute.
 Following is the syntax of using mailto instead of using http.

**Opening Links ina New Window**
How to open a link in a new window or new tab.??!
In order to open a link in a new window / tab, add` target="_blank" ` inside the `<a>` tag:

`<a href="../html-link.htm" target="_blank">Open page in new window</a>`

## Layout :
### Positioning Elements

#### Building Blocks:
1. Block-level elements
2. Inline elements
#### Containing Elements:
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.
#### Controlling the
Position of Elements:
in CSS  to control
the layout of a page:
* normal flow :The paragraphs appear one
after the other, vertically down
the page.
`position:static`

* relative positioning: This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed.
`position:relative`

* absolute positioning: This positions the element
in relation to its containing
element.
`position:absolute`

 
**When you move
any element from
normal flow, boxes
can overlap. The
z-index property
allows you to control
which box appears.
on top `z-index
`**

* To indicate where a box should be positioned, you may also need to use
`box offset` properties to tell the browser how far from the top or bottom
and left or right it should be placed.


*Floating Elements* `float`
The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.
`right` `left` `none` `both`

### Screen Sizes
### Screen Resolution
### Page Sizes
### Fixed Width Layouts:Fixed width layout
designs do not
change size as the
user increases
or decreases
the size of their
browser window.
Measurements tend
to be given in pixels.
### Liquid Layouts:Liquid layout designs
stretch and contract
as the user increases
or decreases the
size of their browser
window. They tend to
use percentages.

### Layout Grids:
. Many designers use a grid structure to help them position items on a page, and the same is true for web designers.
### CSS Frameworks
CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS
framework code in your projects rather than writing the CSS from scratch.
CSS frameworks offer different modules and tools:

* reset style sheet
* grid especially for responsive web design
* web typography
* set of icons in sprites or icon fonts
* styling for tooltips, buttons, elements of forms
* parts of graphical user interfaces like accordion, tabs, slideshow or modal windows (Lightbox)
* equalizer to create equal height content
* often used CSS helper classes (left, hide)

## Functions :
 Programmers use:

1. functions
2. methods
3. objects
 to organize their code.

What is a function ?
A JavaScript function is a block of code designed to perform a particular task.

---> function is executed when "something" invokes it (calls it).
function is defined with the function `keyword` followed by a `name` followed by `parentheses ()`.

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}
`function name(parameter1, parameter2, parameter3) {
  // code to be executed
}`

##Pair Programming:

pair programing is one way we foster a collaborative environment while developing key industry skills.

1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness




































which page you want to link to using the href attribute.

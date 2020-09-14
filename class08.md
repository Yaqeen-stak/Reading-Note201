# Layout :
Positioning Elements
Building Blocks:
CSS treats each HTML element as if it is in its
own box. This box will either be
1. a block-level box (`<h1>` `<p>` `<ul>` `<li>`)
2. an inline box (`<img>` `<b>` `<i>`)

**Containing Elements**
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.
Containing Elements
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.


CSS has the following **positioning schemes** that allow you to control
the layout of a page: 
* normal flow
* relative positioning 
* absolute positioning. 
You specify the positioning scheme using the position
property in CSS.

BOX OFFSET:
To indicate where a box should be positioned, you may also need to use
box offset properties to tell the browser how far from the top or bottom
and left or right it should be placed.

* Fixed Positioning :This is a form of**( Absolute
positioning)** that positions
the element in relation to the
browser window, as opposed
to the containing element.
Elements with fixed positioning
do not affect the position of
surrounding elements and they
do not move when the user
scrolls up or down the page.
* Floating Elements: Floating an element allows
you to take that element out
of normal flow and position
it to the far left or right of a
containing box



### Normal Flow

`position:static`

### Relative Positioning
`position:relative`


### Absolute Positioning

`position:absolute`

### Fixed Positioning

`position:fixed`

WE USE FLOAT TO Place Elements Side-by-Side

 *The following three CSS
properties are used to position
the columns next to each other:
1. width

This sets the width of the
columns.
2.float

This positions the columns next
to each other.
3.margin

This creates a gap between the
columns.

Because screen sizes and display resolutions vary so much, web
designers often try to create pages of around **960-1000 pixels** wide
(since most users will be able to see designs this wide on their screens)

#### Fixed Width Layouts:
Fixed width layout
designs do not
change size as the
user increases
or decreases
the size of their
browser window.
Measurements tend
to be given in pixels.

#### Liquid Layouts:
Liquid layout designs
stretch and contract
as the user increases
or decreases the
size of their browser
window. They tend to
use percentages.

*The liquid layout uses
percentages to specify the width
of each box so that the design
will stretch to fit the size of the
screen*

#### Layout Grids
Grids set consistent proportions
and spaces between items which
helps to create a professional
looking design.
**960 Pixel wide, 12 Column Grid**































*


















































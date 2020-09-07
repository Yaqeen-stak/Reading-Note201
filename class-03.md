# HTML 
## LISTS :
There is three types of lists in HTML :
- Ordered lists

The ordered list is created with `<ol>` element 

Each item in the list is placed between an opening `<li>` tag and a closing `</li>` tag

Note that is use numbers.

- Unordered lists
The unordered list is created with the `<ul>` element.
Each item in the list is placed between an opening `<li>` tag and a closing `</li>` tag


Note that is usebullets.
- Definition lists 
The Definition list is created with `<dl>` element.
inside `<dl>` we will use `<dt>` and `<dd>` elements .

Note that is used to define terminology.

You can put another list inside the `<li>` element

## BOXES :
All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout.

In a document, each element is represented as a rectangular box. Determining the size, properties — like its color, background, borders aspect — and the position of these boxes is the goal of the rendering engine.

In CSS, each of these rectangular boxes is described using the standard box model. This model describes the content of the space taken by an element. Each box has four edges:
* the margin edge
* border edge :The border-width property is used to control the width of a border. 
You can control the style of a border using the border-style property also border-color
* padding edge 
* content edge


The pic below describe the consept.

![Boxes](https://azahreba.gitbooks.io/html101/content/02_css/img/box-model.png)

To set your own dimensions for a box you can use the  height and width properties.

#### **Overflowing Content**
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have
one of two values:
1. hidden: 

This property simply hides any
extra content that does not fit in
the box.
2. scroll:

This property adds a scrollbar to
the box so that users can scroll
to see the missing content.

##### Change Inline/Block
The display property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page.
The values this property can take are:
* inline
* block
* inline-block
* none
###### Border Image
border-image
The border-image property
applies an image to the border of
any box. It takes a background
image and slices it into nine
pieces. 

And we can control the  Box Shadows, Rounded Corners,Elliptical Shapes


# JavaScript :
### ARRAYS :
JavaScript arrays are used to store multiple values in a single variable.
All values evaluate to either truthy or falsy. 
#### VALUES IN ARRAYS 
Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one). 


### Decisions and Loops :
### SWITCH STATEMENTS 
The switch statement is used to perform different actions based on different conditions.
##### The break Keyword:

When JavaScript reaches a break keyword, it breaks out of the switch block.

This will stop the execution of inside the block.

It is not necessary to break the last case in a switch block. The block breaks (ends) there anyway.
##### The default Keyword:

The default keyword specifies the code to run if there is no case match

## Loops :

1. For loop :

to run the code specific number of times .

2. While loop :

when u don't know how many times the code will run.

3. Do While loop :

it will always run the statments inside the curly braces at least ones even it's false .




















# Tables
The `<table>` element is used
to create a table. The contents
of the table are written out row
by row.

`<tr>` (The tr stands for table row.) 
`<td>`  (The td stands for table data.)
`<th>` (Used just like the `<td>` element but its purpose is to represent the heading for either a column or a row)

`<thead>` :
The headings of the table should
sit inside the `<thead>` element.

`<tbody>`:
The body should sit inside the
`<tbody>` element.

`<tfoot>`:
The footer belongs inside the
`<tfoot>` element.


You can make cells of a table span more than one row
or column using the rowspan and colspan attributes

# Functions, Methods, and Objects 

Once you have created an object, the syntax for
adding or removing any properties and methods
from that object is the same. 
`THIS`
The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means.
 It always refers
to one object, usually the object in which the function operates.

**A FUNCTION IN GLOBAL SCOPE**

When a function is created at the top level of a script
(that is, not inside another object or function), then it
is in the global scope or global context. 

**GLOBAL VARIABLES**

All global variables also become properties of the
window object. so when a function is in the global
context, you can access global variables using the
window object, as well as its other properties. 

**A METHOD OF AN OBJECT**

When a function is defined inside an object, it
becomes a method. In a method, this refers to the
containing object. 

**FUNCTION EXPRESSION AS METHOD**

If a named function has been defined in global
scope, and it is then used as a method of an object,
this refers to the object it is contained within. 

## STORING DATA 
In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key. 

#### WHAT ARE BUILT-IN
OBJECTS? 

Browsers come with a set of built-in objects that represent things like the
browser window and the current web page shown in that window. These
built-in objects act like a toolkit for creating interactive web pages.


The first thing you need to do is get to know what tools are available.
You can imagine that your new toolkit has three compartments: 

1. BROWSER OBJECT MODEL

The Browser Object Model contains
objects that represent the current
browser window or tab.
2.DOCUMENT OBJECT MODEL

The Document Object Model uses
objects to create a representation of
the current page.
3. GLOBAL JAVASCRIPT OBJECTS

The global JavaScript objects
represent things that the JavaScript
language needs to create a model
of

###THE BROWSER OBJECT MODEL:

THE WINDOW OBJECT
The window object represents the current
browser window or tab


### THE DOCUMENT OBJECT MODEL: 

The topmost object in the Document Object Model (or DOM) is the
document object. It represents the web page loaded into the current
browser window or tab. 

### GLOBAL OBJECTS:

STRING O BJECT 

Whenever you have a value that is a string, you can use the properties
and methods of the String object on that value.
 
### GLOBAL OBJECTS:

NUMBER OBJECT 
Whenever you have a value that is a number,
you can use the methods and properties of the
Number object on it. 

##### DATA TYPES REVISITED 

In JavaScript there are six data types:
Five of them are described as simple (or primitive) data types.
The sixth is the object (and is referred to as a complex data type). 

1. String

2. Number

3. Boolean 

4. Undefined 
5. Null
6. Objects


As with the String object the
properties and methods of the
Number object can be used with
with any value that is a number. 

### GLOBAL OBJECTS:

MATH OBJECT

The Math object has properties and methods
for mathematical constants and functions. 

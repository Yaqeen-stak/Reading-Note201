# OBJECTS :
JavaScript objects can have properties, which define their characteristics.
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object,
variables and functions take on new names. 
- variables called **property** 
- functions called **methode**
*There are sevsral ways to create an aobjecr BUT the easiest one is **literal notation***


![Objects](https://www.bookofnetwork.com/images/javascript-images/JS_Object-literal---Ways-of-accessing-object-property_04Oct16_1421.png)

The **Document Object Model** (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window. 

As a browser loads a web page, it creates a model of that page.
The model is called a **DOM tree**, and it is stored in the browsers' memory.
It consists of four main types of nodes.

##### DOM Nodes:
According to the W3C HTML DOM standard, everything in an HTML document is a node:

* The entire document is a document node
* Every HTML element is an element node
* The text inside HTML elements are text nodes
* Every HTML attribute is an attribute node (deprecated)
* All comments are comment nodes 

Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes. 
Method that find the element in the DOM tree called **queries**:
DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes.

DOM trees have four types of nodes:
1. document nodes
2. element nodes
3. attribute nodes 
4. text nodes. 

When sotring an element in a variable ,accually we are store the location for this element in DOM tree.

To select indivdual element use :
1.`getElementById()` :get El ementByi d () allows you to select a single element node by specifying the value of its id attribute. 
2.`getQuerySelector()`

When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element). 

SELECTI NG ELEMENTS USING CLASS ATTRIBUTES :`get El ementsByCl ass Name() `
SELECTING ELEMENTS BY TAG NAME : `get El ementsByTagName () `
SELECTING ELEMENTS USING CSS SELECTORS : `querySe 1 ector()`

#### Repeting actions for an intire nodelist :
You can loop through each node in the collection and apply the same statment for each of them.

##### Looping through a nodelist: Play-By-Play 

### TRAVERSING THE DOM :
When you have an element node, you can select
another element in relation to it using these five
properties. This is known as traversing the DOM. 
1. parentNode 

2. previousSibling 

3. nextSibling 

4. firstChild 
5. lastChild 

Traversing the DOM can be difficult because
some browsers add a text node whenever they
come across *whitespace* between elements.

## GET/UPDATE ELEMENT CONTENT :

*ACCESS & UPDATE A TEXT
NODE WITH NODEVALUE*
When you select a text node, you can retrieve or amend the content of it
using the node Va 1 ue property. 
..> To work with text in an element,
first the element node is
accessed and then its text node. 
The text node has a property
called `nodeValue` which returns
the text in that text node.
You can also use the `nodeVa1ue`
property to update the content
of a text node. 
### Adding or Removing HTML content :
That will happen in two ways only :
1. `innerHTML` property .. (Using the i nnerHTML property, you can access and amend the contents of an element, including any child elements.)
2. DOM manipulation  .. (offers another technique
to add new content to a page) 
 It involved 3 steps :
     * `createEl ement () `
     * `createTextNode()`
     * `appendChild() `

**There is three techniques for adding HTML to a web page.** 
## 1. document.write()  

| ADVANTAGES                                                          | DISADVANTAGES                         |
|-------------------------------------------------------------------|-------------------------------------------------------------------|
| It is a quick and easy way to show beginners how content can be added to a page |It only works when the page initially loads.  |
|                                                             |It can cause problems with XHTML pages that are strictly validated. |
|                                                             |This method is very rarely used by programmers these days and is generally frowned upon. |  

## 2. Element.innerHTML 

| ADVANTAGES                                                          |DISADVANTAGES                         |
|-------------------------------------------------------------------|-------------------------------------------------------------------|
| You can use it to add a lot of new markup using less code than DOM manipulation methods. | It should not be used to add content that has come from a user  |
|It can be faster than DOM manipulation when adding a lot of new elements to a web page. |It can be difficult to isolate single elements that you want to update within a larger DOM fragment. |


## 3. DOM MANIPULATION 

| ADVANTAGES                                                          | DISADVANTAGES                        |
|-------------------------------------------------------------------|-------------------------------------------------------------------|
| It is suited to changing one element from a DOM fragment where there are many siblings.  | f you have to make a lot of changes to the content of a page, it is slower than i nnerHTML.  |
|It does not affect event handlers. |You need to write more code to achieve the same thing compared with i nnerHTML.| 


If you add HTML to a page using i nnerHTML (or several jQuery methods),
you need to be aware of **Cross-Site Scripting Attacks** or **XSS**; otherwise,
an attacker could gain access to your users' accounts. 




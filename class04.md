## HTML Links
Links are found in nearly all web pages. Links allow users to click their way from page to page.

HTML Links - Hyperlinks
HTML links are hyperlinks.

You can click on a link and jump to another document.

When you move the mouse over a link, the mouse arrow will turn into a little hand.

Note: A link does not have to be text. A link can be an image or any other HTML eleme
**HTML Links - Syntax**

The HTML <a> tag defines a hyperlink. It has the following syntax:

<a href="url">link text</a>

**Absolute URLs vs. Relative URLs**
Both examples above are using an absolute URL (a full web address) in the href attribute.

A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):


Example
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>

**HTML Links - Use an Image as a Link**
To use an image as a link, just put the <img> tag inside the <a> tag:

Example
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

**Link to an Email Address**
Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email):

Example
<a href="mailto:someone@example.com">Send email</a>

**Button as a Link**
To use an HTML button as a link, you have to add some JavaScript code.

JavaScript allows you to specify what happens at certain events, such as a click of a button:

Example
<button onclick="document.location='default.asp'">HTML Tutorial</button>
# css layout
Each technique can be learned in greater detail in subsequent tutorials. CSS page layout techniques allow us to take elements contained in a web page and control where they are positioned relative to their default position in normal layout flow, the other elements around them, their parent container,...Floats
Floating an element changes the behavior of that element and the block level elements that follow it in normal flow. The element is moved to the left or right and removed from normal flow, and the surrounding content floats around the floated item.

The float property has four possible values:

left — Floats the element to the left.
right — Floats the element to the right.
none — Specifies no floating at all. This is the default value.
inherit — Specifies that the value of the float property should be inherited from the element's parent element.
In the example below we float a <div> left, and give it a margin on the right to push the text away from the element. This gives us the effect of text wrapped around that box, and is most of what you need to know about floats as used in modern web design.
**Grid Layout**
While flexbox is designed for one-dimensional layout, Grid Layout is designed for two dimensions — lining things up in rows and columns.

Once again, you can switch on Grid Layout with a specific value of display — display: grid. The below example uses similar markup to the flex example, with a container and some child elements. In addition to using display: grid, we are also defining some row and column tracks on the parent using the grid-template-rows and grid-template-columns properties respectively. We've defined three columns each of 1fr and two rows of 100px. I don’t need to put any rules on the child elements; they are automatically placed into the cells our grid has created.
Columns

Content is placed in the areas of the screen that contain columns. Column width is defined using percentages, rather than fixed values, to allow content...

Content is placed in the areas of the screen that contain columns.

Column width is defined using percentages, rather than fixed values, to allow content to flexibly adapt to any screen size. The number of columns displayed in the grid is determined by the breakpoint range (a range of predetermined screen sizes) at which a screen is viewed, whether it’s a breakpoint for mobile, tablet, or another size.
![layout](https://visme.co/blog/wp-content/uploads/2018/03/How-Grids-Can-Help-You-Create-Professional-Looking-Designs-Composite-Grids.png)

## about JavaScript
we need to create so many code in our project so when we need to organis the project we need to use function and method and object Functions let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements).
## How i can declerating a function
function name_fun()
{
console.log('hello');
}
## How to call afunction 
function name_fun()
{
console.log('hello');
}
name_fun();
## How to declerating a function return a value
 function sum(num1,num2)
 {
return num1+num2;
 }
FUNCTIONS & OBJECTS BUILT-IN 
METHODS OBJECTS 
Functions consist  you saw that The browser comes with 
series of statements programmers use objects a set of objects that act 
that have been grouped to create models of the like a toolkit for creating 
together because they world using data, and that interactive web pages. 
perform a specific task. objects are made up of This section introduces 
**A method** is the same as a properties and methods. you to a number of built-in 
function, except methods In this section, you learn objects, which you will 
are created inside (and are how to create your own then see used throughout 
part of) an object. objects using JavaScript. the rest of the book. 

 Methods are functions stored as object properties.

Accessing Object Methods
You access an object method with the following syntax:

objectName.methodName()
You will typically describe fullName() as a method of the person object, and fullName as a property.

The fullName property will execute (as a function) when it is invoked with ().

This example accesses the fullName() method of a person object:

Example
name = person.fullName();
![about function](https://miro.medium.com/max/2106/1*65-jFc67sI1B5zRm_91vyQ.png)
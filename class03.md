About html include :
* list using html
Working with HTML Lists
HTML lists are used to present list of information in well formed and semantic way. There are three different types of list in HTML and each one has a specific purpose and meaning. Unordered list — Used to create a list of related items, in no particular order.
HTML lists allow web developers to group a set of related items in lists.
Unordered HTML List
An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.

The list items will be marked with bullets (small black circles) by default:

Example
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
Ordered HTML List
An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.

The list items will be marked with numbers by default:

Example
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
HTML Description Lists
HTML also supports description lists.

A description list is a list of terms, with a description of each term.

The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each term:

Example
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>

How do you make a box in HTML?
Using CSS to Draw a Border Around Your Block of Text and Pictures
Create the HTML for the block. For this tutorial, I shall use a DIV block to enclose the text/pictures. <div class="boxed"> ...
Next, you will need to style the DIV box by adding a border. In your CSS section, or external CSS file, add the following code:
## How do you make a box in HTML?
How do you put a box around text in HTML?
Using Inline Style attribute
Step 1: Firstly, we have to type the Html code in any text editor or open the existing Html file in the text editor in which we want to use the inline property for adding the border.
Step 2: Now, place the cursor inside the opening tag of that text around which we want to add the border.
# looping in javascript
##### switch
##### The switch statement evaluates an expression, matching the expression's value to a case clause, and executes statements associated with that case, as well as statements in ##### cases that follow the matching case.
##### let expr = 'Papayas';
##### switch (expr) {
  ##### case 'Oranges':
   ##### console.log('Oranges are $0.59 a pound.');
   #####  break;
  ##### case 'Mangoes':
  ##### case 'Papayas':
   #####  console.log('Mangoes and papayas are $2.79 a pound.');
    ##### // expected output: "Mangoes and papayas are $2.79 a pound."
   #####  break;
  ##### default:
  #####  console.log(`Sorry, we are out of ${expr}.`);
}
instraction About javascript:
avaScript is commonly used for creating web pages. It allows us to add dynamic behavior to the webpage and add special effects to the webpage. On websites, it is mainly used for validation purposes. JavaScript helps us to execute complex actions and also enables the interaction of websites with visitors.
JavaScript is a programming language commonly used in web development. It was
 originally developed by Netscape as a means to add dynamic and interactive elements to websites. ... For example, a JavaScript function may check a web form before it is submitted to make sure all the required fields have been filled out
 avaScript is a programming language commonly used in web development. It was originally developed by Netscape as a means to add dynamic and interactive elements to websites. While JavaScript is influenced by Java, the syntax is more similar to C and is based on ECMAScript, a scripting language developed by Sun Microsystems.

JavaScript is a client-side scripting language, which means the source code is processed by the client's web browser rather than on the web server. This means JavaScript functions can run after a webpage has loaded without communicating with the server. For example, a JavaScript function may check a web form before it is submitted to make sure all the required fields have been filled out. The JavaScript code can produce an error message before any information is actually transmitted to the server.

Like server-side scripting languages, such as PHP and ASP, JavaScript code can be inserted anywhere within the HTML of a webpage. However, only the output of server-side code is displayed in the HTML, while JavaScript code remains fully visible in the source of the webpage. It can also be referenced in a separate .JS file, which may also be viewed in a browser.

###### Below is an example of a basic JavaScript function that adds two numbers. The function is called with the parameters 7 and 11. If the code below were included in the HTML of a webpage, it would display the text "18" in an alert box.

##### <script>
  function sum(a,b)
  {
    return a + b;
  }
 #####  var total = sum(7,11);
 ##### //alert(total);
</script>


**java script (arrays)**

An array is a special type of variable. It doesn't just store one value; it stores a list of values. You should consider using an array whenever you are working with a list or a set of values that are related to each other. Arrays are especially helpful when you do not know how many items a list will contain because, when you create the array, you do not need to specify how many values it will hold. If you don't know how many items a list will contain, rather than creating enough variables for a long list (when you might only use a small percentage of them), using an array is considered a better solution.

**CREATING AN ARRAY**

You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array). The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array. This technique for creating an array is known as an array literal. It is usually the preferred method for creating an array. You can also write each value on a separate line: colors= ['white', 'black', 'custom'];

**VALUES IN ARRAYS**

Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).

NUMBERING ITEMS IN AN ARRAY Each item in an array is automatically given a number called an index. This can be used to access specific items in the array.
Consider the following array which holds three colors:

var col ors;

colors= ['white ' , 'black ' , ' custom'];

Confusingly, index values start at 0 (not 1), so the following table shows items from the array and their corresponding index values: INDEX VALUE o 'white ' 1 'black' 2 'custom'

ACCESSING & CHANGING VALUES IN AN ARRAY


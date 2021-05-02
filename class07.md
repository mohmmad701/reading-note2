# **What is HTML table?**

The HTML <table> element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data


The <table> tag defines an HTML table. Each table row is defined with a <tr> tag. ... Each table data/cell is defined with a <td> tag. By default, the text in <th> elements are bold and centered. By default, the text in <td> elements are regular and left-aligned
 create table in HTML, use the <table> tag. A table consist of rows and columns, which can be set using one or more <tr>, <th>, and <td> elements. A table row is defined by the <tr> tag. To set table header, use the <th> tag
 HTML <table> tag
Updated: 08/02/2020 by Computer Hope
HTML table tag
When writing in HTML, the <table> tag is a block element used to create a table. It is useful when you want to represent data using rows and columns. The basic elements that make up a table include <th>, <td>, and <tr>. The following sections contain information about the <table> tag, including an example of it in use, and related attributes and browser compatibility.
<table class="mtable2 tab">
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr class="tcw">
    <td>March</td>
    <td>$200</td>
  </tr>
  <tr class="tcw">
    <td>April</td>
    <td>$300</td>
  </tr>
  <tr class="tcw">
    <td>May</td>
    <td>$250</td>
  </tr>
</table>




# the function and object and method in javascript

**Method**
JavaScript methods are actions that can be performed on objects. A JavaScript method is a property containing a function definition. Methods are functions stored as object properties.
var person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};
The this Keyword
In a function definition, this refers to the "owner" of the function.

In the example above, this is the person object that "owns" the fullName function.

In other words, this.firstName means the firstName property of this object.

Read more about the this keyword at JS this Keyword.

**Function**
A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.
JavaScript a function allows you to define a block of code, give it a name and then execute it as many times as you want. A function can be defined using function keyword and can be executed using () operator. A function can include one or more parameters.
  A function is a mapping from a set of inputs (the domain) to a set of possible outputs (the codomain). The definition of a function is based on a set of ordered pairs, where the first element in each pair is from the domain and the second is from the codomain.

  function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
 myFunction(1*2)

 **Object**
 
JavaScript object is a standalone entity that holds multiple values in terms of properties and methods. Object property stores a literal value and method represents function. An object can be created using object literal or object constructor syntax.

An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method. In addition to objects that are predefined in the browser, you can define your own objects.
Like all JavaScript variables, both the object name (which could be a normal variable) and property name are case sensitive. You can define a property by assigning it a value. For example, let's create an object named myCar and give it properties named make, model, and year as follows:

var myCar = new Object();
myCar.make = 'Ford';
myCar.model = 'Mustang';
myCar.year = 1969;

var myCar = {
    make: 'Ford',
    model: 'Mustang',
    year: 1969
};
![example](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS/mdn-graphics-instantiation-2-fixed.png)

What is the object and the DOM using javascrript

## JavaScript Object Model:
In JavaScript, objects are king. If you understand objects, you understand JavaScript.

In JavaScript, almost "everything" is an object.

Booleans can be objects (if defined with the new keyword)
Numbers can be objects (if defined with the new keyword)
Strings can be objects (if defined with the new keyword)
Dates are always objects
Maths are always objects
Regular expressions are always objects
Arrays are always objects
Functions are always objects
Objects are always objects
JavaScript Primitives
A primitive value is a value that has no properties or methods.

A primitive data type is data that has a primitive value.

JavaScript defines 5 types of primitive data types:

string
number
boolean
null
undefined
Primitive values are immutable (they are hardcoded and therefore cannot be changed).

if x = 3.14, you can change the value of x. But you cannot change the value of 3.14.
Objects are Variables
JavaScript variables can contain single values:

Example
var person = "John Doe";
var person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
![objectjavascript](https://miro.medium.com/max/795/1*rSHmnlUotrjc5lXV1xDtGA.png)






## What is the DOM?
The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page.

A Web page is a document. This document can be either displayed in the browser window or as the HTML source. But it is the same document in both cases. The Document Object Model (DOM) represents that same document so it can be manipulated. The DOM is an object-oriented representation of the web page, which can be modified with a scripting language such as JavaScript.
For example, the standard DOM specifies that the querySelectorAll method in the code below must return a list of all the <p> elements in the document:

const paragraphs = document.querySelectorAll("p");
// paragraphs[0] is the first <p> element
// paragraphs[1] is the second <p> element, etc.
alert(paragraphs[0].nodeName);
![DOM](https://www.google.com/search?q=Document+Object+Model&sa=X&stick=H4sIAAAAAAAAAONwlZIMz0gsUcgsVnDx91XIzFPwSixLDE4uyiwokeICCd3YcmPjjbVSPDdbb-y82XazUyElPxfMW36z_WYHSJeUqEt-cmlual6Jgn9SVmpyiYJvfkpqjhQHSHtJUWqqlBDCULA1BSlpUnwgRl5iWWZ6Yklmfp4SdkMsmKJ0yqEOLMlIVciHyCXmpYC5Lvm5IDdnAY0vBhsPAJCEkB_RAAAA&biw=1366&bih=657&sxsrf=ALeKk02zFHLGMsYYe-NkrZxRbIaoQC2mww:1619985315827&tbm=isch&source=iu&ictx=1&fir=_BxVc0nQrD9NgM%252CV7Z9UTu_L9M_iM%252C%252Fm%252F02f7z&vet=1&usg=AI4_-kQvi0kS0y8YNaKPQqERQf5aLDUDDw&ved=2ahUKEwi-2KnK46vwAhWwhf0HHXf-DGEQ_B16BAgoEAE#imgrc=u-SJHMnZV8yt7M)
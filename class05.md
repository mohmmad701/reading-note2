# HTML
## HTML Images**
![iamges](https://www.barmaje.com/images/html.png)
Images can improve the design and the appearance of a web page.
**HTML Images Syntax**
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
Syntax
<img src="url" alt="alternatetext">
<img src="pic_trulli.jpg" alt="Italian Trulli">
**The src Attribute**
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.
**Example:**
<img src="img_chania.jpg" alt="Flowers in Chania">
**The alt Attribute**
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:

**Example**
<img src="img_chania.jpg" alt="Flowers in Chania">

**Image Size - Width and Height**
You can use the style attribute to specify the width and height of an image.

Example
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
**Images in Another Folder**
If you have your images in a sub-folder, you must include the folder name in the src attribute:

Example
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

**Image as a Link**
To use an image as a link, put the <img> tag inside the <a> tag:

Example
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
**Image Floating**
Use the CSS float property to let the image float to the right or to the left of a text:

Example
<p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
The image will float to the right of the text.</p>

<p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
The image will float to the left of the text.</p>
**Background Image on a HTML element**
<div style="background-image: url('img_girl.jpg');">
**Background Cover**
If you want the background image to cover the entire element, you can set the background-size property to cover.

Also, to make sure the entire element is always covered, set the background-attachment property to fixed:

This way, the background image will cover the entire element, with no stretching (the image will keep its original proportions):

Example
<style>
body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}
</style>

**IMAGE FORMATING:**
1.	.apng
2.	.gif
3. .ico, .cur
4. .jpg, .jpeg, .jfif, .pjpeg, .pjp
5. .png

## HTML Colors
![color](https://i.pinimg.com/originals/7b/f7/c6/7bf7c6e53128592dcd608f368571821c.gif)
HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
**Background Color**
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
**Text Color**
<h1 style="color:Tomato;">Hello World</h1>
**Border Color**
<h1 style="border:2px solid Tomato;">Hello World</h1>
**Color Values**
In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

The following three <div> elements have their background color set with RGB, HEX, and HSL
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
## HTML Text Formatting


HTML Formatting Elements
![text](https://cdn.educba.com/academy/wp-content/uploads/2019/06/HTML-Format-Tags-1.jpg)
Formatting elements were designed to display special types of text:

<b> - Bold text <b>This text is bold</b>
<strong> - Important text
<i> - Italic text //<i>This text is italic</i>
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text





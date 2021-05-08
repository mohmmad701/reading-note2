 ## Read: 11 - Assorted Topics
**From Duckett HTML Book:** 
Ch. 16: "Images" (pp.406-427)
Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup.

You can control the size of an image using the width and height properties in CSS, just like any other box.
In addition to the float property, you can use the align attribute.
Background images can be used using an example like this: body {background-image: url("images/pattern.gif");}
Repeating images can be used with the folowing example: body { background-image: url("images/header.gif"); background-repeat: repeat=x;}
Image rollovers is achieved by setting a background image for the link or button that has three different styles of the same button.
When an single image is used for several different parts of an interface, it is known as a sprite. The advantage of using sprites is that the web browser only needs to request on image rather than many images, which can make the page load faster.(pg.417-418)
Ch. 19: "Practical Information" (476-492)
Launching a successful site key themes:

 ## The basics of search engine optimization
Using analytics to understand how people are using your site after it has launched.
Putting your site on the web.
You can use google analytics and sign up for an account. This site will give you a piece of tracking code which you need to push on every page of your site.

Every time someone loads a page of your site, the tracking code sends data to the google servers where it is store. Google then provides a web based interface that llows you to see how visitors use your site.
The tracking code should appear just before the closing </head> tag.
In order to put your site on the web you will need a domain name and web hosting.

 ## Your domain name is your web address (URL).
Ch. 9: "Flash" (pp.201-206 only)
Since the late 90's, Flash has been a very popular tool for creating animations, and later for playing audio and video in websites. Flash didn't keep up with its namesake super hero meta human, however, and wasn't quick enough to keep up with the changing tech world around it as the time line on page 205-206 ends at 2011. (insert tombstone gif)

**MDN:** Video and Audio API's
HTML5 comes with elements for embedding rich media in documents - <video> and <audio> - which in turn come with their own APIs (Application programming interface) for controlling playback, seeking, etc. Interface - A device or program enabling a user to communicate with a computer.

When it comes to <video> <audio> you need to specify playback controls or they won't do anything. The attribute is controls which enables the default set of playback controls.

HTML5 spec, the HTMLMediaElement API provides features to allow you to control video and audio players programmatically. For example HTMLMediaElement.play(), HTMLMediaElement.pause(), etc. This interface is available to both A and V elements.

For more detail visit MDN article: Video and Audio APIs

Table of Contents
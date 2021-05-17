 ## Docs for the HTML <canvas> Element & Chart.js
 **What is Chart.js?**

Chart.js is an open-source data visualization library.

HTML5 charts using JavaScript render animated charts with interactive legends and data points. 
**How do you use Chart.js?**

Built using JavaScript, Chart.js requires the use of the HTML <canvas> element and a JS function to instantiate the chart. 

Datasets, labels, background colors, and other configurations are then added to the function as needed.

 What is covered in this Chart.js tutorial?

**We will cover the following topics:**

 ### Chart.js Installation
npm
bower
CDN
### Chart.js Integration
Chart.js HTML
Chart.js JS
### Chart.js Charts
Line
Radar
Doughnut
Pie
Polar area
Bubble
Scatter
Area
Mixed
### Chart.js Configurations
Chart title 
Chart legends
Chart padding
Integration - How to add Chart.js to an HTML document

Chart.js requires HTML and JavaScript code.

The HTML code places the chart in the document using the <canvas> element while the JavaScript function instantiates the chart.

 

How to add the Chart.js <canvas> element

How to display Chart.js in an HTML template

<!DOCTYPE html>
<html>
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chart.js Integration</title>
    <!--Chart.js JS CDN--> 
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.9.4/Chart.min.js"></script> 
  </head>
  <body>

    <div>
	<canvas id="myChart"></canvas>
    </div>
  
  
  </body>
</html>
Chart.js requires a <canvas> element containing the unique id of the chart for the data to render in the HTML template.

This is the only HTML code required.
![example about the canvas](https://images.slideplayer.com/24/7231192/slides/slide_30.jpg)

![example the chart ](https://cms-assets.tutsplus.com/uploads/users/1451/posts/27197/preview_image/cover.jpg)
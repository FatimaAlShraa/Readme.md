# Chart
 
it's display data visually so great way to get started with charts is with Chart.js
+ first thing we need to do is download Chart.js

 < script src='Chart.min.js' >< /script > 

+ Drawing a line chart

first thing we need to do is create a canvas element in our HTML

< canvas id="" width="" height="">< / canvas >
then we need to write a script that will retrieve the context of the canvas, so add this to the foot of html

+ Drawing a pie chart

First, we need the canvas element then we  get the context and to instantiate the chart

+ Drawing a bar chart
First, we add the canvas element then retrieve the element and create the graph

*The < canvas > 

< canvas > element has only two attributes, width and heigh
Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback
 content to be displayed by those browsers.

## Drawing shapes with canvas

+ Drawing rectangles

function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.fillRect(25, 25, 100, 100);-------- > Draws a filled rectangle

    ctx.clearRect(45, 45, 60, 60);----------> Draws a rectangular outline

    ctx.strokeRect(50, 50, 50, 50);--------> Clears the specified rectangular area, making it fully transparent
  


+ Drawing paths

 ctx.beginPath(); -------> Creates a new path

    ctx.moveTo(75, 50); ------> Methods to set different paths for objects

    ctx.lineTo(100, 75); ----->Adds a straight line to the path

    ctx.lineTo(100, 25); -----> Draws the shape by stroking its outline
    
    ctx.fill(); -----> Draws a solid shape by filling the path's content area
  }

## Applying styles and colors

+ Colors

fillStyle = color ----> Sets the style used when filling shapes

strokeStyle = color ---> Sets the style for shapes' outlines

The shadowColor property is a standard CSS color value indicating the color of the shadow effect; by default, it is fully-transparent black

+ CanvasGradient

We create a CanvasGradient object by using one of the following methods. We 
can then assign this object to the fillStyle or strokeStyle properties. 

**Drawing text**

canvas rendering context provides two methods to render text:

+ fillText ---> Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

+ strokeText ---> Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.


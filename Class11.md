' use strict';

# Readings: Chart.js, Canvas

# JavaScript Canvas

1. What does the <canvas> allow a developer to acheive?

- <canvas> element that allows you to draw 2D graphics using JavaScript.
The <canvas> element requires at least two attributes: width and height
that specify the size of the canvas:

2. What is the importance of the closing `</canvas> tag?
-contains fallback content that will display only if the browser doesn’t support the <canvas> element.

Explain what the getContext() method does.

- the getContext() method that returns a render context object.
The getContext() takes one argument which is the type of context.

# Chart js. Documentation

1. What is Chart.js and how it can be brought into your project?
-To create a chart, we need to instantiate the Chart class, pass in the node, jQuery instance, or 2d context of the canvas of where we want to draw the chart,Once you have the element or context, you're ready to instantiate a pre-defined chart-type or create your own

2. List 3 different Chart types you can create using Chart.js.

- Line Chart
- Bar Chart
- Pie Chart

# Easily Create Stunning Animated Charts with chart.js

1. What are some advantages to displaying data via a chart over a table?

- Graphs can show a large amount of data quickly in a way that is easy to process, without distracting people with a bunch of numbers

2. How could Chart.js aid your previously created applications visually?

- By making it more intuitive 'spice up your data
  - - Remove background lines
Remove default line margins

# Drawing shapes with canvas

Drawing rectangles- <canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths

There are three functions that draw rectangles on the canvas:

1. The CanvasRenderingContext2D.fillRect() method of the Canvas 2D API draws a rectangle that is filled according to the current fillStyle.

2.he CanvasRenderingContext2D.strokeRect() method of the Canvas 2D API draws a rectangle that is stroked (outlined) according to the current strokeStyle and other context settings.

3.The CanvasRenderingContext2D.clearRect() method of the Canvas 2D API erases the pixels in a rectangular area by setting them to transparent
black.

# Drawing path

A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:

1. First, you create the path.
2. Then you use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.

Here are the functions used to perform these steps:

beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.

Path methods
Methods to set different paths for objects.

closePath()
Adds a straight line to the path, going to the start of the current sub-path.

stroke()
Draws the shape by stroking its outline.

fill()
Draws a solid shape by filling the path's content area


## Lines

For drawing straight lines, use the lineTo() method.

lineTo(x, y)
Draws a line from the current drawing position to the position specified by x and y.

## Arcs
To draw arcs or circles, we use the arc() or arcTo() methods.

arc(x, y, radius, startAngle, endAngle, counterclockwise)
Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction indicated by counterclockwise (defaulting to clockwise).

arcTo(x1, y1, x2, y2, radius)
Draws an arc with the given control points and radius, connected to the previous point by a straight line.

## Curves

A Bézier curve (pronounced [bezje]) is a mathematically described curve used in computer graphics and animation. In vector images, they are used to model smooth curves that can be scaled indefinitely.

# Applying Style and Colors - Canvas API
## Colors

to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

fillStyle = color
Sets the style used when filling shapes.

strokeStyle = color
Sets the style for shapes' outlines.

# Drawing Text - Canvas API

The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

A fillText example
The text is filled using the current fillStyle.

# Styling Text 

There are some more properties which let you adjust the way the text gets displayed on the canvas:

font = value
The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.

textAlign = value
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

textBaseline = value
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

direction = value
Directionality. Possible values: ltr, rtl, inherit. The default value is 
inherit.


# Advanced text measurement
to obtain more details about the text, the following method allows you to measure it.

measureText()
Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.






color is a string representing a CSS <color>, a gradient object, or a pattern object.

# **Chart.**

 great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. 

 It's easy to get started with Chart.js. All that's required is the script included in your page along with a single <canvas> node to render the chart.
 


 ## Also you can Drawing shapes with canvas

Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high

 <canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.

First let's look at the rectangle. There are three functions that draw rectangles on the canvas:

* fillRect(x, y, width, height)
Draws a filled rectangle.
* strokeRect(x, y, width, height)
Draws a rectangular outline.
* clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.
Each of these three functions takes the same parameters. x and y specify the position on the canvas (relative to the origin) of the top-left corner of the rectangle. width and height provide the rectangle's size.

vas.

## Drawing paths
Now let's look at paths. A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:

First, you create the path.
Then you use drawing commands to draw into the path.
Once the path has been created, you can stroke or fill the path to render it.
Here are the functions used to perform these steps:

* beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
Methods to set different paths for objects.
* closePath()
Adds a straight line to the path, going to the start of the current sub-path.
* stroke()
Draws the shape by stroking its outline.
* fill()
Draws a solid shape by filling the path's content area.
The first step to create a path is to call the beginPath(). Internally, paths are stored as a list of sub-paths (lines, arcs, etc) which together form a shape. Every time this method is called, the list is reset and we can start drawing new shapes.

## Applying styles and colors
If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

* fillStyle = color
Sets the style used when filling shapes.
* strokeStyle = color
Sets the style for shapes' outlines.
color is a string representing a CSS //<color>, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).


## Drawing text
The canvas rendering context provides two methods to render text:

*fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
* strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
* A fillText example
The text is filled using the current fillStyle.



you can download chart from [CHART](https://github.com/chartjs/Chart.js.git)
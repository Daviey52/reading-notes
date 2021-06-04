# class Twelve

[Home](https://daviey52.github.io/reading-notes/)

## Charts , Canvas

* charts are far better at displaying data visually than tables. they are easier to look at and convey data quickly.

* Chart.js is a JavaScript plugin that uses HTML5's canvas elements to draw the graph onto the page. it can make all kinds of bar charts , line charts , pie charts among others.

* it is very easy to get started with Chart.js, all that is required is the script included in the page and a canvas node to render the chart.

* Setting up includes copying the Chart.min.js into the html page you will be using. Then writing a script that retrives the context of the canvas to add it to the appropriate location in a document.

* The great thing about chart.js is that its simple to use and very flexible plus it offer alot of options.

* The canvas element has only two attributes, that is; Width and height.

* The canvas element can be styled just like a normal image ( margin , border , background). These rules don't affect actual drawing on the canvas.

* Canvas only supports two primitive shapes: rectangles and paths( list of points connected by line). All other shapes must be created by combining one or more paths.

* A path is a list of points, connected by segments of lines that can be of different shapes , curved or not of different width or of different color. To make shapes using paths, we take the following steps

1. create the path
2. use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.

* Bezier curves are types of paths that are available in both cubic and quadratic varieties. They are used to draw complex organic shapes.

* Path2d API is a powerful feature of the new canvas that uses SVG path Data to initalize paths on a canvas. This allows the user to pass around path data and re-use them in both, SVG and canvas.

* The lineJoin property determines how two connecting segments with non-zero length in a shape are joined together.There are three possible values for this property: bevel , round and miter.

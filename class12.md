# chart.js

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.
**The great things about Chart.js are that it’s simple to use and really very flexible**
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.
## License
Chart.js is available under the MIT license.
# The `<canvas>` element:
 the <canvas> element has only two attributes, `width` and `height` .
When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. 
## Fallback content
Providing fallback content is very straightforward: just insert the alternate content inside the <canvas> element.

### The rendering context
The `<canvas>` element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown.

# The grid
 Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0).
All elements are placed relative to this origin.

### Drawing paths:
To make shapes using paths, we take some extra steps:

1. First, you create the path.
2. Then you use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.


### Moving the pen:

One very useful function, which doesn't actually draw anything but becomes part of the path list described above, is the moveTo() function. You can probably best think of this as lifting a pen or pencil from one spot on a piece of paper and placing it on the next.
`moveTo(x, y)` :
Moves the pen to the coordinates specified by x and y.
### Lines

For drawing straight lines, use the lineTo() method.

`lineTo(x, y)`
Draws a line from the current drawing position to the position specified by x and y.

### Arcs

To draw arcs or circles, we use the ``arc() or` arcTo()` methods.


arc(x, y, radius, startAngle, endAngle, anticlockwise)
Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction indicated by anticlockwise (defaulting to clockwise).

### Rectangles
`rect(x, y, width, height)`
Draws a rectangle whose top-left corner is specified by (x, y) with the specified width and height.

### Path2D objects

As we have seen in the last example, there can be a series of paths and drawing commands to draw objects onto your canvas. To simplify the code and to improve performance, the Path2D object, available in recent versions of browsers, lets you cache or record these drawing commands.

# styles and colors :
If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
`fillStyle = color`
Sets the style used when filling shapes.

`strokeStyle = color`
Sets the style for shapes' outlines.

## Transparency

In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

`globalAlpha = transparencyValue`
The globalAlpha property can be useful if you want to draw a lot of shapes on the canvas with similar transparency, but otherwise it's generally more useful to set the transparency on individual shapes when setting their colors.

**miterLimi**
The `miterLimit` property determines how far the outside connection point can be placed from the inside connection point

# Drawing text 

The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

# Styling text
`font = value`

The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.

`textAlign = value`

Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

`textBaseline = value`

Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

`direction = value`

Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.

## Advanced text measurements
In the case you need to obtain more details about the text, the following method allows you to measure it.

`measureText()`
Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.


















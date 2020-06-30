# Creating graphs
``` <canvas id="tutorial" width="150" height="150"></canvas> ```
- canvas is the start of a graph and only attributes are width and height
- you can style ```<canvas>``` with margin, border, background
- getContext() is a method for canvas used to obtain the rendering context and its drawing function
- canvas only supports to shapes 
  - rectangles
  - paths (points connected with lines)
- other shapes can be achieved by combining one or more paths
## functions for rectangle
``` fillRect(x, y, width, height) ```
``` strokeRect(x, y, width, height) ```
``` clearRect(x, y, width, height) ```
## drawing paths 
```beginPath()```
```closePath()```
```stroke()```
```fill()```
## other shapes
- drawing triangles 
- arcs
- bezier and quadratic curves
- cubic bezier curves
## applying styles and colors 
- colors 
  ```fillStyle = color``` (sets the style when filling shapes)
  ```strokeStyle = color``` (sets the style for shape outlines)
- transparency 
  ```globalAlpha = transparencyValue``` (sets a specified transparency 0.0 fully transparent 1.0 fully opaque)
## line styles 
- line width
- line cap
- line join
## gradients
- createLinearGradient
- createRadialGradient
- Patterns
- shadows
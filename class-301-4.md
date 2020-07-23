# Responsive Web Design and Regular Expressions
Display
- Defines the element as a grid container and establishes a new grid formatting context for its contents.
Values of grid
- grid, inline-grid

grid-template-columns, grid-template-rows
- Defines the columns and rows of the grid with a space-separated list of values. The values represent the track size, and the space between them represents the grid line

grid-template-areas
- Defines a grid template by referencing the names of the grid areas which are specified with the grid-area property. Repeating the name of a grid area causes the content to span those cells. A period signifies an empty cell. The syntax itself provides a visualization of the structure of the grid.
- grid-area
- . (empty cell)
- none

justify-items
- Aligns grid items along the inline (row) axis (as opposed to align-items which aligns along the block (column) axis). This value applies to all grid items inside the container.
- start
- end 
- center
- stretch

## Children properties  
grid-column-start
grid-column-end
grid-row-start
grid-row-end
grid-column
grid-row
grid-area
justify-self
align-self
place-self
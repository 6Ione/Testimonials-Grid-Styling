# Personal Notes taken

# Grids
* When creating multiple grids based off a layout we use grid-template-columns/rows to create the columns and rows (200px or desired).
   grid-template-columns: 200px 200px 200px;
   grid-template-rows: 200px 200px;

  * columns and rows can be used as grid-auto-columns/rows automatically but gives less control of the design.

* Naming the <div> with the style attribute helps style the grid area across the columns and rows.
<div class="box" style="grid-area: box1">

* For mobile viewing making the grid 'thinner' helps and looks pleasing
compared to compact overlapping designs.

* Depending on the screen size the grid-template-areas can be changes to fit properly.
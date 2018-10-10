# Thomasclaude/grid.v1

- Client: __ThomasClaude__
- Project: __Grid__
- Type: __Project__
- Version: __1.0.0__

## Getting started

- Clone the grid
- Pick the assets file and put it in your project folder
- Add the files's path in your `index.html` and the other page you want to display the grid

## Customizing

- You can customize the style of the grid like
  - The color of the column/gutter
  - The content of the displaying button
  
- But the most important is the possibility of making you own grid size

To make that you need to change these value in the main.js


var myGrid = {

  gridWidthUnit: "vw", // Works in % and px too 
  
  gridWidth: 85, // Most of time i'm filing this on my '.container' class's width
  
  gridGutterWidthUnit: "vw", // Works in % and px too 
  
  gridColumnNumber: 12, // Better keep 12 for desktop
  
  gridGutterWidth: 2,
  
  activateGrid: false
  
};


setGridLayout(myGrid);


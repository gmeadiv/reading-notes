# Chart.js, Canvas

## Getting started
- <script src="https://cdn.jsdelivr.net/combine/npm/chart.js@3.5.1,npm/chart.js@3.5.1/dist/chart.esm.js,npm/chart.js@3.5.1/dist/chart.js,npm/chart.js@3.5.1/dist/helpers.esm.js"></script>
- <script src="https://cdn.jsdelivr.net/npm/chart.js@3.5.1/dist/chart.min.js"></script>
- <script src="https://cdn.jsdelivr.net/npm/chart.js@3.5.1/dist/chart.esm.js"></script>
- <script src="https://cdn.jsdelivr.net/npm/chart.js@3.5.1/dist/chart.js"></script>
- <script src="https://cdn.jsdelivr.net/npm/chart.js@3.5.1/dist/helpers.esm.js"></script>

## Creating a chart
- [Instructions](https://www.chartjs.org/docs/latest/)
- [Different types of charts](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)
  - line chart
  - pie chart
  - bar chart

## Basic usage of canvas
- the < canvas > element
  - two attributes: width and height
  - default size is 300x150px
  - specify WxH explicitly in canvas attributes not CSS
  - can be styled like any other image
  - with no styling rules canvas will be transparent
- the rendering context
  - the canvas element creates a fixed size drawing surface that exposes one or more rendering contexts, used to create and manipulate the content shown

## Drawing shapes with canvas
- [Instructions](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

## Applying styles and colors
- [Instructions](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

## Drawing text
- [Instructions](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)
- fillText: fills a given text at the specified (x,y) position
- strokeText: strokes a given text at the specified (x,y) position
- styling text
  - font: default is 10px sans-serif
  - textAlign: default is start
  - textBaseline: default is alphabetic (other values include top, hanging, middle, ideographic, bottom)
  - direction: default is inherit

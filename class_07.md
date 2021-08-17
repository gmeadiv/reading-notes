# Object-Oriented Programming, HTML Tables

## Domain Modeling
- the process of creating a conceptual model in code for a specific problem
  - articulated well, it can verify and validate the understanding of a specific problem among technical and business teams
  - object-oriented models store data in properties and encapsulates behaviors in methods
- EpicFailVideo
  - Property: epicRating; hasAnimals
  - Data: 1-10; true or false
  - Type: number; boolean
  - e.g. EpicFailVideo = function(epicRating, hasAnimals) {
    this.epicRating = epicRating;
    this.hasAnimals = hasAnimals;
  }
  var parkourFail = new EpicFailVideo(7, false);
  var corgiFail = new EpicFailVideo(4, true)

  ## Tables
  - <table> element adds a table to the page
  - a table is drawn out by row created with the <tr> element
  - inside each row are cells created by the <td> element
  - cells can span more than one row using the rowspan and colspan attributes
  - long tables can be split into <thead> <tbody> and <tfoot>

## Functions, Methods, and Objects
-  browser object model: contains objects that represent the current browser window/tab (ie browser history and device screen)
- document object model: uses objects to create a representation of the current page
- global javascript objects: represents things that JS needs to create a model of (ie dates and times)
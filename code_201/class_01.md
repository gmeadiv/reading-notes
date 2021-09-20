# Intro to HTML
## Structure
- Hyper text markup language creates the structure of a webpage, similar to the frmaing of a house
- HTML uses elements to describe the structure
    - each element has an opening and closing tag
    - information is in between the tags
    - everything within the body element is shown inside the main browser window

## Extra Markup
- ID attribute
    - every element can carry an id attribute
    - used to uniquely identify that element from other elements on the page
    - allows same elements to be styled differently in CSS
    - also known as a global attribute
- Class attribute
    - also a global attribute
    - groups several different elements together to be styled the same
    - the value should describe the class it belongs to
- Block elements
    - start a new line on the browser window
    - headers, paragraphs, lists
- inline elements
    - continue on the same line as their neighboring elements
- Grouping text & elements
    - in a block: < div > element
    - inline: < span > element
- Iframes
    - < iframe > cuts a little window into the web page through which another page can be seen
    - src specifies the URL of the page in the frame
    - height and width: self explanatory
- Escape characters
    - HTML reserves the use of some characters for coding purposes (eg angle brackets)
    - Make sure ampersands and such are properly written so they show up on the web page

## HTML5 Layout
- Traditional HTML layouts used div elements to group related elements together on the page
- HTML5 offers new elements that divide up the page

## Process and Design
- websites should be designed for the user
    - individuals
    - companies
- why is the user coming to my site?
- what does the user expect, what do they need?
- how often will they visit?

# Intro to JavaScript
## What is a script?
- a series of introductions a computer can follow step-by-step
- similar to a recipe or repair manual
- state the goal and then list the tasks needed to accomplish it
    - vocabulary: words that computers understand
    - syntax: how those words are put together creates instructions computers can follow
    - need to think programmatically

## How do computers fit in with the world around them?
- Objects & properties
    - objects are things
    - properties are characteristics
        - each property has a name and a value
- Events
    - changes the values of the properties in objects
- Methods
    - represent how people interact with an object
    - can retrieve or update the values of an object's properties

## Lecture Notes
- Inline styling and script
    - the old way of inserting styling and script directly into the html
    - now we separate this code "separation of concerns"
    - makes code organized and easier to read
    - easier to debug
    - easier for teams to all work on one application at once
    - still useful to know bc i may encounter legacy code one day
- to add code for script and styling inline
    - for styling add a 'style' attribute directly to an element:
        - <h1 style="color: green">Welcome to Class</h1>

## internal styles
- styles added to the head of the html document within a style element
- set rules for the entire document
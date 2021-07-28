# Design web pages with CSS
## What is CSS?>
- Cascading Style Sheets
    - controls how HTML elements look in the browser
- CSS Syntax
    - rules based language
    - opens with *selector* which chooses the HTML element that is to be styled
    - inside curly braces { } will be one or more *declaration* 
    - which take the form of *property* and *value* pairs specifying a property of the element we are selecting and a value we are giving to the property
    - before the colon is the property; after the colon is the value (ie color: red)
- CSS Modules
    - breaks down categories of what is styled by CSS for easy access
- CSS Specifications
    - CSS is developed within a group made of folks who have an interest in maintaining standards for CSS
- Browser support information
    - different browser may support different parts of CSS and not others

## How to add CSS
- Three ways to insert CSS
    1. External CSS 
    - defined within the < link > element inside the < head > section of an HTML page
    - can be written in any text editor and must be saved with a .css extension
    2. Internal CSS
    - may be used if one single HTML page has a unique style
    - defined inside the < style > element inside the < head > section
    3. Inline CSS
    - may be used to apply a unique style for a single element
    - defined within the "style" attribute of the relevant element
- Cascading Order
    - when more than one style is specified for an HTML element, the styles will "cascade" in order:
    1. Inline style
    2. External and internal style sheets
    3. Browser default

## CSS color property
- Definition and Usage
    - Use a background color combined with a text color that makes the text easy to read
    

# HTML Links, JS Functions, and Intro to CSS Layout
## Links
- Example: <a href="https://twitter.com/gmeadiv">This is my twitter</a>
  - href is the address of the page i want the user to go to
  - the text between the tags is what the user will see and click on
  - absolute URLs are for linking to different websites
  - relative URLs are for linking to pages within the same site (eg my table of contents)

## Layouts
- positioning
  1. static-type: default position of any element
  2. relative-type:
    - relative: elements can be moved out of their position while leaving a space where its original position is/was
      - is positioned relative to its original position
    - absolute: similar to relative positioning but will not leave a space for original position
      - is positioned relative to a parent element's position
    - fixed
    - sticky
- floats
- flexbox (week 2)
- grid (week 3)

## Display
- all HTML elements have inherent display values
  - CSS allows us to alter how the HTML element is viewed
- Inline: eg **bold** is inline with the other text
  - won't change height or width
- Inline-block:
  - allows programmer to adjust width and height of inline text
- Display block:
  - element gets its own line and takes up entire width of the page

## Functions, Methods, and Objects
- functions and methods: 
  - series of statements grouped together because they perform a specific task
  - method is the same as a function except that methods are created inside of an object
  - functions are stored within a structure that prevents them from running until it is called/invoked
  - functions will always return some value, even if it's undefined
  - when we *define* a function we use parameters to declare variables
  - when we *call/invoke* the function, we use arguments to assign values to the variables
- objects
- built-in objects

## 6 Reasons for Pair Programming
- practice of two developers sharing a single workstation to interactively tackle a coding task together
- two roles:
  - driver: person typing
  - navigator: thinks about the big picture, what's next, how an algorithm might be converted into code, scans for bugs and typos
1. Greater efficiency
  - easier to catch mistakes in the moment
  - takes longer at first but produces higher quality code that needs less revision later
  - one programmer can take over when the other gets stuck
2. Engaged collaboration
  - programmers focus better with a partner around
  - less need for additional help
3. Learning from fellow students
  - exposes programmers to different techniques and ideas
4. Social skills
  - builds communication
  - forced to deal with different personalities
5. Job interview readiness
  - pairing an applicant with an employee is a common step during the interview process
6. Work environment readiness
  - employers expect to train fresh hires with pair programming

## Using JS within markup
``` javascript
function bakeACake
let marryMe = driveByTruckers

```
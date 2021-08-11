# HTML Lists, Control Flow with JS, and the CSS Box Model
## Lists
- ordered/numbered lists
- unordered/bullet lists (this is an unordered list!)
- definition lists (ie a dictionary)
- nested lists (list within a list)

## Boxes
- controlling their size
  - default setting is to be just big enough to hold its contents
  - size can be absolute or relative to the user's screen
  - overflow tells the browser what to do if the stuff in the box is bigger than the box itself
    - can hide any extra content
    - add a scroll bar
    - adding overflow property helps user adjust the size of the text
- box model for borders, margin, and padding
  - man, bear, pig
      1. Margins are on the very outside and can create a gap between the borders of two adjacent boxes
        - setting left- or right-margin to auto centers the content
        - need to set a width when centering or content will take up entire page
      2. Borders separate the edge of one box from another
      3. Padding is the space between the border and the content within (helps increase the readability of its contents)
        - not inherited so needs to be specified for every element that uses it
  - white space and vertical margin
    - padding and margin help add space between items on the page
- displaying and hiding boxes
  - width
    - four sizes goes clockwise: top, right, bottom, left
    - or two sizes: left-right; top-bottom
    - or one size
  - style
    - solid
    - dotted
    - dashed
    - double
    - groove
    - ridge
    - inset
    - outset
    - hidden/none
  - color
  - shorthand: one line in this order (width); (style); and (color)

 ## Decisions
  - Logical and
  - Logical or not
  - If statements
    - If ... else
  - Switch statements
    - starts with a variable called switch value
    - each case indicates a value for the variable and if the variable matches, a specific code is run
    - default case if no variable matches
  - Type coercion: JS converts a data type behind the scenes to complete an operation
    - this is called weak typing
  - Falsy values
    - traditional boolean false
    - the number zero
    - empty string
    - not a number (the value i get if i try to do math with numbers and strings)
    - variable with no value assigned to it
  - Truthy values (anything that isn't falsy is truthy)
    - traditional boolean true
    - numbers other than zero
    - strings with content
    - number calculations
    - zero written as a string
    - false written as a string
  
## Loops
- loops check a condition, and if it returns true, the loop runs a code block
  - cycle will continue as long as the condition remains true
  - infinite loops can crash my computer! BE CAREFUL!
  - keeps us from writing the same code over and over
  - allows for ambiguity and flexibility when writing code
- 3 types of loops
  1. FOR a specific number of times
  2. WHILE the condition is true
  3. 'Do...while' will run the code at least once, even if the condition is false
- anatomy of a FOR loop
  - for (let count = 0; count < 10; count ++)
  - ('for' keyword);('let count' variable declaration);('count <' conditional expression);('count++' condition changes)
  - i = 'index'
  - i++  is shorthand for 'i = i+1'
  - EXAMPLE: for (let i = 0; i < cardArray.length; i++) {}
- anatomy of a WHILE loop
  - EXAMPLE: while (startValue < 10){
    console.log(startValue);
    startValue = startValue +1;
  }
  - EXAMPLE: let allCardsBlack = true; 
    - let index = 0;
    - while (allCardsBlack === true || index > cardColor.length)
    - if (cardColor[index] === 'red') {
      allCardsBlack = false;
    - console.log('I found a red card')
    }
    - index++

## Comparison Operators
- a == b (loose equality)
  - a can have the same value as b, but they don't have to be the same type
  - 10 == '10'
  - BUT 10 !== '10'
- a === b (strict equality)
  - both the type and the value have to be the same
- a != b (loose inequality)
  - 10 != '10' (false!)
- a !== b (strict inequality)
  - 10 !== '10' (true!)
- a > b / a < b (greater than/less than)
- a >= b / a <= b (greater than or equal to/less than or equal to)

## Logical Operators
- a && b (a and b)
- a || b (a or b)
- !a (not a/opposite of a) - bang!
- JS reads L to R
  - if a isn't true, for 'a && b' it won't go to b
  - if a is true, for 'a || b' it won't go to b

## Arrays
- type of object that is arranged as a list of elements
  - can be made of any type of element
  - can be a mismatch of elements
  - not always best practice to make an array of different data types
  - number of elements in the array doesn't need to be predetermined
  - every element in an array has an index (location reference)
  - based on a zero index system (first element is actually 'zero')
- to add a new value to the end of my array
  - name of array (dot) push method
  - EXAMPLE: snackArray.push(new value)
- to add an value to the beginning of my array
  - name of array (dot) unshift method
  - EXAMPLE: snackArray.unshift(new value)
- to find a value's position in the array
  - (dot) indexOf
- to remove a value from the array
  - (dot) slice()

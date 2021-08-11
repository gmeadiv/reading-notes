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
  

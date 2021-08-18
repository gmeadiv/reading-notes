# CSS Layout

## Layout
- Building Blocks
  - css treats each html element as its own box
  - block-level elements start on a new line (h1, p, ul, li)
  - inline elements flow in between surrounding text (img, b, i)
- contianing elements
  - when one block-level element sits inside another block level element, the outer box is known as the contianing or parent element
- positioning schemes
  - normal flow: every block-level element appears on a new line
    - position:static
  - relative positioning: positions element in relation to its normal flow position, does not affect other elements
    - position:relative
  - absolute positioning: positions element in relation to its parent element, does not affect other elements, moves up and down as user scrolls thru page
    - position absolute
  - fixed positioning: positions element in relation to the browser window, does not affect other elements, does not scroll with page
    - position:fixed
  - floating elements: takes element out of normal flow, positions element to far right or left of the parent box, floated element becomes block-level element around which other elements flow 
  - box offset properties: tells browser how far from top/bottom or left/right a box should be placed
  - z-index property: controls which box is on top in case of overlapping boxes

  ## Flexbox
  - layout: positioning, float, display
    - pros: lets us move things
    - cons: can move other things on the page, makes it hard to predict, not super logical
  - flexbox:
    - section > div tags
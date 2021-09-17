# Putting it all together

## Thinking in react
- start with a mock
- step one: break the UI into a component hierarchy
  - single responsibility principle states a component should only do one thing
- step two: build a static version in react
  - takes in data model and renders UI but has no interactivity
  - building a static version requires lots of typing but little thinking
  - adding interactivity requires a lot of thinking but little typing
  - don't use this.state bc that's data changed by user interaction
  - can build top-down (for small projects) or bottom-up (for large projects)
- step three: id the minimal but complete representation of UI state
  - DRY: don't repeat yourself
- step four: id where state should live
  - most challenging part is understanding what component should own/mutate what state
  - for every piece of state
    1. id every component that renders something based on that state
    2. find a common owner component (must be above in hierarchy all the components that need the state)
    3. either the common owner or another component higher up in the hierarchy should own the state
    4. if no component makes sense, create one!
- step five: add inverse data flow

## Higher-Order Functions
- functions that operate on other functions by taking them in as arguments or returning them
- greaterThan function
  - this function takes in an argument "n" and line two creates another function which compares "n" to "m"
- script data set
- filtering arrays
  - forEach
  - filter
- transforming with map
  - applies a function to all of an array's elements and builds a new array from the returned values
  - new array will have the same length as the old one
- summarizing with reduce
  - builds a value by repeatedly taking a single element from an array and combines it with the current value
- composability
- strings and character codes
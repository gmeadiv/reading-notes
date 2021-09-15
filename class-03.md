# Passing Functions as Props

## Lists and Keys
- rendering multiple components
- basic list component
- Keys: help react id which items changed, were added or removed
- extracting components with keys
  - keys only make sense in the context of the surrounding array
  - elements inside the map() call require keys
- keys must be unique among siblings
- embedding map() in JSX

## How to use the spread operator
- spread syntax refers to the use of an ellipsis to expand an iterable object into a list of arguments
- ... can:
  - copy and array
  - concatenating or combining arrays
  - using math functions
  - using an array as arguments
  - adding an item to a list
  - adding a state in react
  - combining objects
  - converting nodelist to an array

## How to pass functions between components
In the video, what is the first step that the developer does to pass functions between components?
- Creates a function
In your own words, what does the increment function do?
- It takes in a name, loops through the objects to find its match, and updates its match's count to reflect how many times the user has selected that name
How can you pass a method from a parent component into a child component?
- key = {this.method}
How does the child component invoke a method that was passed to it from a parent component?
- this.props.method()
# FUNCTIONAL PROGRAMMING

## Concepts
- What is functional programming?
  - A style of building the structure and elements of a program that treats computation as the evaluatoin of mathematical functions and avoids changing-state and mutable data
- What is a pure function and how do we know if something is a pure function?
  - it returns the same result if given the same arguments
  - it does not cause observable side effects
  - doesn't read external files
  - doesn't rely upon a random number generator
- What are the benefits of a pure function?
  - easire to test
- What is immutability?
  - data whose state cannot be changed after creation
- What is Referential transparency?
  - purse functions + immutable data = referential transparency

## Modules and require()
- What is a module?
  - splits code up into different moduoes for different bits of code according to their funcitonality
  - essentially, just another .js file
- What does the word ‘require’ do?
  - finds a JS file, reads it, executes it, and returns the export object
- How do we bring another module into the file the we are working in?
  - declare a variable which = require([name of the module to be imported])
- What do we have to do to make a module available?
  - module.exports = [name of the module we want to export]
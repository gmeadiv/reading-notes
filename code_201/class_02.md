# Basics of HTML, CSS, and JS
## Text
- Structural markup: elements that can be used to describe both headings and paragraphs
- Semantic markup: provides extra information, ie where is info placed in a sentence, text is quoted, meaning of acronyms, etc.

## Introducing CSS
- If HTML is the woodframing of a house, CSS is the design
- CSS Selectors
  - targets rules to specific elements
  - universal: applies to all elements * {}
  - type: matches element names h1, h2, h3 {}
  - class: matches an element whose class attricute has a value that matches .note {}; p.note{}
  - ID: matches an element whose id attribute has a value that matches #introduction {}
  - Child: matches an element that is a direct child of another li>a {}
  - Descendant: matches an element that is a descendant of another p a {}
  - Adjacent sibling: matches an element that is the next sibling of another h1+p {}
  - General sibling: matches an element that is any sibling of another h1~p {}
- not all browser display css the same

## Basic JS Instructions
- a script is a set of instructions a computer can follow one-by-one
- a statement is an individual instruction and ends with a semicolon
- comments explain what my code does
- scripts store data in variables
- Data types
  - numbers
    - decimals
    - negative
    - written with no special notation
  - string (of words)
    - can also contain numbers and symbols
    - denoted with 'single quotation marks'
  - boolean (true or false)
    - logical data type
    - no special notation
    - used a lot in validation
  - undefined
    - self-explanatory
    - default while variable is waiting to be defined
  - null
    - variable is explicitly declared as null
    - different from the number ZERO (more absolute)
- Six rules for naming variables
  1. name must begin with a letter, dollar sign, or underscore, it CANNOT begin with a number
  2. the rest of the name can contain letters, numbers, dollar sign, or underscore, must NOT use a dash or a period in the name
  3. cannot use keywords/reserved words
  4. all variables are case sensitive
  5. use a name that describes the information
  6. multiple word names capitalize the beginning of each word AFTER the first word
- An array is a type of variable that stores a list of values
- An expression results in a single value
  - expressions that just assign a value to a variable
  - expressions that use two or more values to return a single value
- Expressions rely on operators to create a single value from one or more values
  - assignment operators assign a value to a variable
  - arithmetic operators perform basic math
  - string operators combine two strings
  - comparison operators compare two values and return true or false
  - logical operators combine expressions and return true or false

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
    - not a number
    - variable with no value assigned to it
  - Truthy values
    - traditional boolean true
    - numbers other than zero
    - strings with content
    - number calculations
    - zero written as a string
    - false written as a string
  
## Loops
- loops check a condition, if it returns true a code block will run
  - cycle will continue as long as the ocndition remains true
- 3 types of loops
  1. FOR a specific number of times
  2. WHILE the condition is true
  3. Do while will run the code at least once, even if the condition is false

  ## Lecture notes
  - data types in JS
    - a way of labeling and organizing data
    - a way to format data that our program can anticipate and use the data properly
    - primitive data types cannot be broken down into something more specific (numbers, strings, booleans, undefined, and null)
  - JS is a loosely typed and dynamic language
    - loosely typed: we don't have to know the type of data in order to declare a variable (ie is it going to be a number or a strong?)
    - in other words, variables don't have to be declared with a type
    - dynamic: the type of data can change after the variable has been declared
- coding w/ JS
  - strict mode: 'use strict'
  - best practice: don't alter the user's input, keep an original, make a new variable if the input needs to be altered
  - prompts always return a string even if user inputs a number!!
    - if i want it to return a number:
    - parseInt(variableName)
    - Number(variableName)
  - switch statement
  - break statement gets out of the switch statement
- CSS styling
  - order of styling
    1. styling that will affect entire document
    2. styling on all text
    3. work from top to bottom by section/element
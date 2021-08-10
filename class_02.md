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
  - numeric
  - string (of words)
  - boolean (true or false)
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

  ## Decisions and Loops
  - 
# In Memory Storage

## Understanding the JS Call Stack
  1. What is a ‘call’?
    - primarily used for calling functions
    - call stack is synchronous
  2. How many ‘calls’ can happen at once?
    - functions are called one at a time from the top to the bottom
  3. What does LIFO mean?
    - Last In, First Out
  4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
  5. What causes a Stack Overflow?
    - when a recursive function (a function which calls itself) doesn't have an exit point

## JS Error Messages
  1. What is a ‘refrence error’?
    - a variable that is not yet declared
  2. What is a ‘syntax error’?
    - code cannot be parsed because it was typed out wrong
  3. What is a ‘range error’?
    - when an object with a length is given an invalid length
  4. What is a ‘tyep error’?
    - This great pun is in fact *not* axample of a 'type' error but a syntax error!
    - type errors show up when the types of data being accessed are incompatible
  5. What is a breakpoint?
    - an intentional stopping point in a program which helps assist in narrowing down the lo0cation of bugs/errors
  6. What does the word ‘debugger’ do in your code?
    - it is a built-in breakpoint
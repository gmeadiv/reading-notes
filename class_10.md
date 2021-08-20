# Error Handling & Debugging

## Order of execution
- execution context
  - global context: code that is in a script but not in a function, only one gloabl context in any page
  - function context: code being run within a function, each function has its own context
  - eval context
  - two phases of activity:
    1. prepare
    2. execute
- variable scope
  - global scope: if a variable is declared outside of a function it has global scope
  - function-level scope: when a variable is declared within a function, it can only be used within that function
- the stack: because js only processes on line of code at a time, when a statement needs data from another function, js stacks the new function on top of the current task

## Understanding errors
- when js encounters an error it will first look for error-handling code
- error objects
  - error
  - SyntaxError
  - ReferenceError
  - TypeError
  - RangeError
  - URIerror
  - EvalError
- debug the script to fix errors
- handle errors gracefully
  - try
  - catch
  - throw
  - finally
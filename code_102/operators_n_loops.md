# Operators and Loops Notes
## Expressions and Operators
- Operators
    - assignment: x = y | x = y
    - addition assignment: x+=y | x = x + y
    - subtraction assignment:
    - multiplication
    - division
    - remainder: x %= y | x = x % y
    - exponent: x **= y | x = x ** y
    - left shift: x <<= y | 
    - right shift:
    - unassigned right shift: x >>>= y
    - bitwise AND: x &= y
    - bitwse XOR: x ^= y
    - bitwise OR: x |= y
    - logical AND: x &&= y
    - Logical OR: x ||= y
    - logical nullish: x ??= y
- return value and chaining
    - return value matches the expression to the right of the = sign in the "meaning" column
- comparison operators
    - = returns true if the operands are equal
    - != (not equal) returns true if operands are not equal
    - === (strict equal) returns true if the operands are equal *and* of the same type
    - !== (strict not equal) returns true if the operands are of the same type but not equal or are of a different type
    - ">" returns true if the left operand is greater than the right operand
    - ">=" greater than or equal
    - < less than
    - <= less than or equal

## Loops and Iteration
- for: repeats until a specified condition evaluates to false
- do ... while: repeats until a specified condition evaluates to false
- while: executes as long as a specified condition evaluates to true
- labeled: provides a statement with an identifier that lets me refer to it elsewhere in my program
- break: terminates a loop
- continue: restarts a loop
- for ... in: iterates a specified variable over all the enumerable properties of an object
- for ... of: creates a lopp over iterable objects invoking a custom iteration hook with statements to be executed for the value of each distinct property
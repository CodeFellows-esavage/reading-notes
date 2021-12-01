# Operators and Loops
Resources:
- [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Loops and Iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#labeled_statement)


## Operators
Operator Types
- Assignment operators - assigns value to the left based on value to the right of the operator
- Comparison operators - compares two values and returns logical value (ex. true or false)
- Arithmetic operators - modifies two values based on the action performed (+, -, *, /, etc)
- Bitwise operators - treats inputs as 32 bits (0's and 1's)
- Logical operators - typically used with Boolean value sand return a Boolean value
- String operators - concatenation (+ when used with a string)
- Conditional (ternary) operator - takes three inputs and results in either va11 or va12 based on whether the condition is true or false
- Comma operator - evaluates both inputs and returns the last one
- Unary operators - delete, this deletes an objects property
- Relational operators - compares the inputs and returns a boolean (`in`)

## Loops and Iteration
Loops reapeat an action some number of times. Different loop types allow for alternate ways to determine the starting and stopping points for a loop.

Loop Types:
- for statement: repeats until a specific condition is found `false`
  - `for ([initialExpression]; [conditionExpression]; [incrementExpression];)`
  - `statement`
    - order of operations:
    - `intialExpression` is executed for one or more loop counters
    - `conditionExpression` evaluates if the condition is `true` or `false`
    - `incrementExpression` if conditions require, executes
    - intial variable value is set in `initialExpression`
    - ![for statement](https://i.pinimg.com/474x/45/b9/26/45b926396f8705983d5d605132341361.jpg)
- do...while statement: repeats until a specific condition is found `false`
  - inital variable value is set outside of the do...while loop
- while statement: executes statement as long as specified condition is `true`
  - condition test happens before the statement is executed
    - ![while loop](https://www.tutorialspoint.com/java/images/java_while_loop.jpg)
- labeled statement: provides an identifier to a statement
- break statement: used to terminate a loop `break;` or `break [label]`
- continue statement: used to restart a while, do-while, for or label statement
  - in a while loop this jumps back to the condition
  - in a for statement it jumps to the `incrementExpression`
- for...in statement: iterates a specified variable over all the enumerable properties of an object
- for...of statement: creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on)


- While loop: use when we don't know how many times we need to run it
- For loop: runs a certain number of times, so when you know how many times or about how many times you need the loop to run.
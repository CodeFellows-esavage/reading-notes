# Programming with JavaScript
Resources:
- [Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
- [Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)


## Expressions and Operators
 
Operator Types

[JavaScript Operators](https://www.w3schools.com/js/js_operators.asp)
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
  
Expression Types:
- Arithmetic: results in a number
- String: results in a character string
- Logical: results in true or false
- Primary expressions: Basic keywords and general expressions in JavaScript.
- Left-hand-side expressions: Left values are the destination of an assignment.

## Functions
[JavaScript Functions](https://www.w3schools.com/js/js_functions.asp)

Function Declarations are intiated by using the `function` declaration keyword followed by the name of the function parentheses () enclosing a list of parameters, and curly braces {} capturing the JavaScript statements that define the function (code to be executed). Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

Note: Inside the function, the arguments (the parameters) behave as local variables.

```
function double(num) {
    return num + num;
}
```

Calling a function:
```
double(5);

returns 10
```

The **only** way to get data store in a variable declared in a function is to `return` that variable at the end of the function.

Variables defined in the function are **ONLY** available in the function.


## Control Flow
Control flow is the order in which the computer executes statements in a script. This order is run from first to last line, unless there is a structure that changes the flow.

Conditionals and Loops are a way to change the flow structure.

Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.







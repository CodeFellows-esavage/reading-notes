# Dynamic Web Pages with JavaScript

Resources:
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Input Output in plain JavaScript](https://code-maven.com/input-output-in-plain-javascript)
- [JavaScript Variables](https://www.w3schools.com/js/js_variables.asp)

## Overview
JavaScript is a lightweight compiled programming language with first class functions (functions are treated like any other variable). It is primarily used as a scripting language for web pages, but is also used in non-browser environments as well.

## Javascript Variables
Variables are containers for storing values and there are three (3) ways to declare them in JavaScript.
1. `var`
2. `let`
3. `const`

```Reference Script
<p id="demo"></p>
<script>
    var x = 5;
    var y = 6;
    var z = x + y;
    document.getElementById("demo").innerHTML =
    "The value of z is: " + z;
</script>
```

### Identifiers
All JavaScript variables **must** be identified with unique names (aka identifiers).

General Rules for Identifiers:
- length can be one (1) digit or longer
- must begin with a letter, $, OR _
  - $ is often used as an alias for the main function in a JavaScript library
  - _ is often used for private or hidden variables
- may contain letters, numbers, $, OR _
- are case sensitive (x and X are considered different)
- cannot be JavaScript keywords

### Assignment Operator
The equal sign `=` is an assignment operator in JavaScript, and not considered equal to (denoted as `==`)

### Data Types
- strings: written in "double" or 'single' quotes
- numbers: written without quotes

### Declaring Variables
Declaring a variable, creates a variable, and can be done with the `var` keyword. When intially created a variable has no assigned value. To assign a value use the assignment operator `=` either in the same line of text as the variable creation, or afterwards on a separate line.

```
var Name;
Name = "Erik";
```

OR

```
var Name = "Erik";
```

Both set name = to "Erik".


Additional Points:
- You can declare multiple variables in one statement.
- Variables declared without a value will be `undefined`.

### Arithmetic
- use `+`, `=` to do simple arithmetic


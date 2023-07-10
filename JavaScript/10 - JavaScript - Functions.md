In JavaScript, functions are fundamental constructs for structuring code and building software. They allow you to encapsulate blocks of code into reusable, callable units. 

Here's an overview of how to create and use functions in JavaScript:

**1. Function Declaration**

A function is defined with the `function` keyword, followed by a name, followed by parentheses `()`. The code to be executed by the function is placed inside curly brackets `{}`:

```javascript
function myFunction() {
    // Code to be executed
}
```

**2. Calling a Function**

You call or invoke the function by using its name followed by parentheses:

```javascript
myFunction();
```

**3. Function Parameters**

Functions can take parameters, which are specified inside the parentheses at the time of function declaration:

```javascript
function myFunction(param1, param2) {
    console.log(param1, param2);
}
```

You pass arguments to the function when calling it:

```javascript
myFunction("Hello", "World"); // Prints: "Hello World"
```

**4. Function Return Value**

A function can return a value using the `return` keyword. Once a function hits a `return` statement, it will stop executing and return the specified value:

```javascript
function add(a, b) {
    return a + b;
}

let sum = add(5, 3); // sum will be 8
```

**5. Function Scope**

Variables declared within a JavaScript function become local to the function. Local variables have function scope and can only be accessed from within the function:

```javascript
function myFunction() {
    let x = 10;
    console.log(x);
}
myFunction(); // Prints: 10
console.log(x); // Error: x is not defined
```

**6. Anonymous Functions**

These are functions that are not given a name. They are usually not accessible after their initial creation. They can be assigned to variables or used as callback functions:

```javascript
let myFunction = function() {
    console.log("Hello World");
};
myFunction(); // Prints: "Hello World"
```

**7. Arrow Functions**

Introduced in ES6, arrow functions provide a more concise syntax for defining functions. They are particularly handy when defining functions to be used for callbacks or promises:

```javascript
const myFunction = (param1, param2) => {
    console.log(param1, param2);
};
myFunction("Hello", "World"); // Prints: "Hello World"
```

Arrow functions also handle the `this` keyword differently than regular functions.

**8. Higher-Order Functions**

In JavaScript, functions can take other functions as arguments, and they can also return other functions. Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. Examples of higher-order functions include `Array.prototype.map`, `Array.prototype.filter`, and `Array.prototype.reduce`.

These are the basic concepts around JavaScript functions. There are more advanced topics like closures, Immediately Invoked Function Expressions (IIFEs), and recursion that you can learn about as you get more comfortable with these basics.

# **LINKS**
[[10.1 - JavaScript - Functions - Things should know]]
[[10.2 - JavaScript - Functions - Differences between Function declarations and Function expression]]
[[10.3 - JavaScript - Functions - Parameters and Arguments]]
[[10.4 - JavaScript - Functions - Type of Functions]]
[[10.5 - JavaScript - Functions - Functions call other functions]]
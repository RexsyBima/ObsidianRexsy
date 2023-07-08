Variable in JavaScript is a named storage for data. It's a way for the programmer to name a value to reuse it within the program. You can think of it as a named box that can store a value.

To declare (create) a variable, we can use the `let`, `const`, or `var` keyword.

Here's an example using `let`:

```javascript
let name;
```

In the code above, we have declared a variable named `name` but we didn't assign any value to it yet. Its value is `undefined` at this point.

You can also assign a value to the variable at the time of declaration:

```javascript
let name = 'Rexsy';
```

The `=` symbol is called the assignment operator. It assigns the value on the right ('Rexsy') to the variable on the left (name).

You can change the value of a variable declared with `let` after it has been set:

```javascript
let name = 'Rexsy';
name = 'Alex'; // 'Alex' is now the value of the variable name
```

`const` works like `let`, but the value of `const` can't be changed after it has been set. It's short for "constant". Here's an example:

```javascript
const pi = 3.14;
pi = 3; // This will throw an error, because you can't change a const.
```

The `var` keyword is older and behaves a bit differently from `let` and `const`, but it's also used to declare variables. It's generally better to use `let` and `const` as they have more predictable behavior.

```javascript
var age = 25;
```

Variables can store data of any type: numbers, strings, objects, functions, etc. You can also use variables in expressions:

```javascript
let a = 5;
let b = 10;
let c = a + b; // c will be 15
```

Understanding how to use variables is fundamental in programming as variables are the basic units of storage in a program. They allow us to capture and manipulate data in our applications.

**LINKS**
[[3.1 - JavaScript - Variables - Rule Parameters Convention]]
[[3.2 - JavaScript - Variables - Declaring Variable with let]]
[[3.3 - JavaScript - Variables - Declaring Variable with const]]
[[3.4 - JavaScript - Variables - Declaring Variable with var]]
[[3.5 - JavaScript - Variables - Why not to Declare Variable without let, const, or var]]
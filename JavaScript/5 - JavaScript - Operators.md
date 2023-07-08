In JavaScript, there are several types of operators. Let's dive into the main ones:

### 1. Arithmetic Operators

Arithmetic operators perform mathematical operations on numbers. 

- Addition (`+`): Adds two numbers.

    ```javascript
    let sum = 10 + 5;  // sum will be 15
    ```

- Subtraction (`-`): Subtracts the second operand from the first.

    ```javascript
    let difference = 10 - 5;  // difference will be 5
    ```

- Multiplication (`*`): Multiplies two numbers.

    ```javascript
    let product = 10 * 5;  // product will be 50
    ```

- Division (`/`): Divides the first operand by the second operand.

    ```javascript
    let quotient = 10 / 5;  // quotient will be 2
    ```

- Modulus (`%`): Returns the remainder of the division of the two operands.

    ```javascript
    let remainder = 10 % 3;  // remainder will be 1
    ```

- Increment (`++`): Increases the value of a variable by 1.

    ```javascript
    let count = 1;
    count++;  // count will be 2
    ```

- Decrement (`--`): Decreases the value of a variable by 1.

    ```javascript
    let count = 3;
    count--;  // count will be 2
    ```

### 2. Assignment Operators

Assignment operators assign a value to a variable.

- Assignment (`=`): Assigns the value from the right side operand to the left side operand.

    ```javascript
    let x = 10;  // x will be 10
    ```

Other assignment operators are a combination of arithmetic operators and the assignment operator.

- Add and assign (`+=`): Adds the value of the right operand to the left operand and assigns the result to the left operand.

    ```javascript
    let x = 10;
    x += 5;  // x will be 15
    ```

- Subtract and assign (`-=`), multiply and assign (`*=`), divide and assign (`/=`), and modulus and assign (`%=`) work in a similar fashion.

### 3. Comparison Operators

Comparison operators compare the values of two operands and return a boolean (`true` or `false`).

- Equal to (`==`): Returns true if the operands are equal.

    ```javascript
    console.log(5 == '5');  // Outputs: true
    ```

- Not equal to (`!=`): Returns true if the operands are not equal.

    ```javascript
    console.log(5 != '6');  // Outputs: true
    ```

- Strictly equal to (`===`): Returns true if the operands are equal and of the same type.

    ```javascript
    console.log(5 === '5');  // Outputs: false
    console.log(5 === 5);    // Outputs: true
    ```

- Strictly not equal to (`!==`), greater than (`>`), less than (`<`), greater than or equal to (`>=`), and less than or equal to (`<=`) work in a similar fashion.

### 4. Logical Operators

Logical operators are typically used with boolean values, and they return a boolean value.

- Logical AND (`&&`): Returns `true` if both operands are `true`.

    ```javascript
    console.log(true && false);  // Outputs: false
    ```

- Logical OR (`||`): Returns `true` if at least one operand is `true`.

    ```javascript
    console.log(true || false);  // Outputs: true
    ```

- Logical NOT (`!`): Returns `true` if the operand is `false`, and vice versa.

    ```javascript
    console.log(!true);  // Outputs: false
    ```

### 5. String Operators

The `+` operator can also be used to concatenate (join) two string values:

```javascript
let greeting = "Hello" + " " + "World";  // greeting will be "Hello World"
```

The `+=` operator can be used to add (concatenate) strings to a variable:

```javascript
let greeting = "Hello";
greeting += " World";  // greeting will be "Hello World"
```

### 6. Ternary Operator

The ternary operator is a shortcut for the `if` statement and is made up of three parts: a condition, a result for when the condition is `true`, and a result for when the condition is `false`.

```javascript
let age = 15;
let beverage = (age >= 21) ? "Beer" : "Juice";
console.log(beverage);  // Outputs: "Juice"
```

In this example, since the `age` is not greater than or equal to `21`, the variable `beverage` gets the value `"Juice"`. If `age` was `21` or more, `beverage` would get the value `"Beer"`.

Remember to always use operators in the context that they're designed for, and to consider the type of the values that you're operating on. JavaScript does provide a lot of flexibility, but with that flexibility comes the potential for some confusing behavior if you're not careful.

**LINKS - REFERENCES**
[[5.x - JavaScript - Operators - Precedence]]
[[5.1 - JavaScript - Operators - Arithmetic Operator]
[[5.2 - JavaScript - Operators - Assignment Operator]]
[[5.3 - JavaScript - Operators - String Operator]]
[[5.4 - JavaScript - Operators - Comparison Operator]]
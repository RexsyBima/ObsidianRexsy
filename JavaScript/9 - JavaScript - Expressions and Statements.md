In JavaScript, the key difference between an expression and a statement is that an expression results in a value, which can then be inserted into code wherever values are allowed. A statement, on the other hand, performs an action and does not necessarily return a value. All expressions can be statements, but not all statements can be expressions.

For instance, any mathematical operation like `2 + 2` or `"Rexsy" + " rocks!"` is an expression because they result in values (`4` and `"Rexsy rocks!"`, respectively). When you use these expressions in your code, they are replaced with the value they produce.

However, when an expression is followed by a semicolon (`;`), it becomes an expression statement, which is one type of statement. Here's an example:

```javascript
let x = 5;  // statement
let y = x * 2;  // another statement, contains an expression 'x * 2'
```

In the above example, `x * 2` is an expression. When used in the line `let y = x * 2;`, it's part of an expression statement.

Control flow structures like `if`, `for`, `while`, etc., are statements because they perform actions but do not themselves produce a value. However, they often contain expressions within them. For example:

```javascript
if (x * 2 > 10) { // 'x * 2 > 10' is an expression, 'if' statement contains this expression.
    console.log("x is greater than 5"); // statement
}
```

In conclusion, JavaScript programs are composed of a series of statements. Some of these statements (like `if` or `while`) contain expressions or even other statements. Expressions, on the other hand, compute values and are often parts of statements. Understanding these concepts will help you better understand the structure and syntax of JavaScript.

**LINKS**
[[9.1 - JavaScript - Expression]]
[[9.2 - JavaScript - Statements]]
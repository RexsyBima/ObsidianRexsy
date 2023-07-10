Absolutely, Rexsy! In JavaScript, the key data structures you'll encounter are Arrays, Objects, Sets, and Maps. 

**1. Arrays**
An array in JavaScript is a data structure that stores multiple values in a single variable. Each element in an array has its own index, starting from 0 for the first element, 1 for the second, and so on.

Here's an example of an array:

```javascript
let fruits = ['apple', 'banana', 'cherry'];
console.log(fruits[0]); // Outputs 'apple'
```

**2. Objects**
JavaScript objects are containers for named values. Each named value in an object is called a property, and functions are called methods. 

Here's an example of an object:

```javascript
let car = {
  make: 'Toyota',
  model: 'Corolla',
  year: 2020,
  start: function() {
    console.log('Car started');
  }
};
console.log(car.make); // Outputs 'Toyota'
car.start(); // Outputs 'Car started'
```

**3. Sets**
A Set is a special type of object introduced in ES6 that only allows unique values - no duplicates are allowed. A value in the Set may only occur once.

Here's an example of a Set:

```javascript
let mySet = new Set();
mySet.add(1);
mySet.add(2);
mySet.add(3);
mySet.add(2); // This won't be added, 2 is already in the Set
console.log(mySet); // Outputs Set { 1, 2, 3 }
```

**4. Maps**
A Map is a simple key-value map and can iterate its elements in insertion order. 

Here's an example of a Map:

```javascript
let myMap = new Map();
myMap.set('name', 'Rexsy');
myMap.set('age', 25);
console.log(myMap.get('name')); // Outputs 'Rexsy'
console.log(myMap.size); // Outputs 2
```

These are the basics of data structures in JavaScript. Each has its own use cases and properties, and they can be combined in various ways to handle more complex data needs.

# **LINKS**
[[11.1 - JavaScript - Data Structures - Arrays]]
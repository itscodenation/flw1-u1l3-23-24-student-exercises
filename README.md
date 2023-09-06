# Lesson 1.3: Documentation, Variables & Data Types

## 🎯 Objectives
- Understand and use JavaScript variables.
- Work with basic data types and operators.

## Table of Contents
1. [Documentation](#documentation)
2. [JavaScript & Variables](#javascript-&-variables)
3. [Data Types & Operators](#data-types-&-operators)


## Documentation
- **Documentation** is crucial for:
  - Understanding code.
  - Using code.
  - Debugging.
  - Collaborating with peers.
- Use the Code Nation Coding Guides to refer to class syntax.
- Remember: Googling is part of a developer's job! Platforms like **W3Schools** and **egghead.io** can be invaluable.

## JavaScript & Variables
![JavaScript Image](https://miro.medium.com/v2/resize:fit:1200/1*LyZcwuLWv2FArOumCxobpA.png)

- **JavaScript** enables dynamic behaviors on a webpage.
- **Variable** is a container that holds data. 
  ```javascript
  let box;
  box = 8;
  ```

### Rules for naming variables:
- Cannot start with a number.
- Cannot be keywords.
  ```javascript
  let mySpiritAnimal = "unicorn";  // Valid
  let thisIsAcceptable = "acceptable";  // Valid
  ```

### Variable Declaration & Assignment:
- We can declare and assign a value to a variable in two steps or in one step.
  ```javascript
  let cake;
  cake = "lemon";
  // OR
  let cake = "lemon";
  ```

- Variables can be reassigned.
  ```javascript
  let myBox = 8;
  myBox = 56;  // myBox is now 56
  ```

## Data Types & Operators

### Data Types
- **Numbers**: Can be positive/negative and may have decimals.
  ```javascript
  let num = 1234;
  let decimalNum = 1.99;
  ```

- **Strings**: Textual data enclosed in quotes.
  ```javascript
  let greeting = "Hello, World!";
  let codeString = "code123";
  ```

### Arithmetic Operators
- Basic operators include: `+`, `-`, `*`, `/`.
  ```javascript
  let num1 = 10, num2 = 5;
  let sum = num1 + num2;  // 15
  ```

- Strings can also be concatenated using the `+` operator.
  ```javascript
  let str1 = "Hello, ";
  let str2 = "World!";
  console.log(str1 + str2);  // Hello, World!
  ```

- Mixing data types can produce unexpected results.
  ```javascript
  console.log(5 + "cat");  // 5cat
  ```


This lesson covered the importance of documentation, declaring variables in JavaScript, the basic data types, and how to perform operations on them. Always remember to refer to documentation when in doubt. 

Keep practicing and happy coding!

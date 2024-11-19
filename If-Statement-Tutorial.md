# Using `if` Statements in JavaScript

![computer with if statements code](https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?w=1000&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8Y29kZSUyMGlmJTIwc3RhdG1lbnR8ZW58MHx8MHx8fDA%3D)

> #### In JavaScript `if` statement used to make decision on wither to execute block of code or not based on a condition. Down is a tutorial on how to use if statement.

## 1. Basic Syntax
```javascript
if (Condition){

//Block of code

};
```
1. `if` **Keyword:** it is a keyword to let JavaScript know that you want to use if statement.
   
2. **Condition:** A logical expretion that will be either ***truthy*** of ***falsy*** 
   
3. **Block of code:** The code that you want it to run if the condition is true

### *Example*
```javascript
const age = 18;

if (age >= 18) {
  console.log("You are an adult");
};
```
## 2. Using `else`

`else` allow to include default option if *all* the conditions are ***falsy***.

### *Example*
```javascript
const num = -5;

if (num > 0) {
  console.log("Positive number");
} else {
  console.log("Negative number");
};
```
## 3. Using `else if`

`else if` allow you to use ***multiple*** conditions in single if statement

### *Example*
```javascript
const grade = 85;

if (grade >= 90) {
  console.log("A");
} else if (grade >= 75) {
  console.log("B");
} else {
  console.log("C");
};
```
For more information visit [MDN if...else docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

## Acknowledgement 

[MDN :](https://developer.mozilla.org/en-US/) used as a refrence for information.


[ChatGPT :](https://chatgpt.com/) used for the **Examples Only**.
1. Write short notes on the below with code examples
   •	while loop
   •	do-while loop
   •	for loop
   •	for in loop
   •	for of loop

Ans. 
* while loop : The while loop in JavaScript is used to execute a block of code repeatedly as long as a specified condition is true.

- Code example :
```js
let i = 0;
while (i < 10) {
  console.log(i);
  i++;
}
```
* do-while loop : A do...while loop in JavaScript is a control structure that executes a block of code at least once, and then repeatedly executes the block as long as a specified condition is true. The key feature of a do...while loop is that the condition is evaluated after the code block has been executed, ensuring that the code block runs at least once regardless of the condition.

- Code example :
```js
let i = 0;
do {
  console.log(i);
  i++;
} while (i < 5);
```
* for loop : The for loop in JavaScript is a control flow statement that allows you to execute a block of code repeatedly based on a condition.

- Code example : 
```js
for (let i = 0; i < 5; i++) {
  console.log("The number is " + i);
}
```
* for in loop : The for...in loop in JavaScript is used to iterate over the enumerable properties of an object.

- Code example :
```js
const person = { name: "John", age: 30, city: "New York" };

for (let i in person) {
  console.log(i + ": " + person[i]);
}  
```
* for of loop : The for...of loop in JavaScript is a powerful way to iterate over iterable objects like arrays, strings, maps, sets, and more. It allows you to loop through the values of an iterable object directly.

- Code example :
```js
const cars = ["BMW", "Volvo", "Mini"];
for (let i of cars) {
  console.log(i);
}
```
2.	Explain the scope in Javascript.

Ans.
Scope determines the accessibility (visibility) of variables, objects, and functions from different parts of your code. There are three main types of scope in JavaScript:

* Global Scope:
** Variables declared outside any function or block have global scope.
** These variables can be accessed from anywhere in the JavaScript code.

* Function Scope:
** Variables declared inside a function are local to that function.
** These variables cannot be accessed from outside the function.

* Block Scope:
** Introduced with ES6, variables declared with let and const inside a block (e.g., {}) have block scope.
** These variables are only accessible within that block.

3.	What is a callback?

Ans.
A callback function is a function that is passed as an argument to another function and is executed after the main function has completed its operation. This allows for more flexible and modular code, especially when dealing with asynchronous operations.

4.	Explain context in JavaScript

Ans.
In JavaScript, the environment that enables the JavaScript code to get executed is what we call JavaScript Execution Context. It is the execution context that decides which code section has access to the functions, variables, and objects used in the code. During the execution context, the specific code gets parsed line by line then the variables and functions are stored in the memory. An execution context is similar to a container that stores variables, and the code gets evaluated and then executed. Thus, it is the execution context that provides an environment for the specific code to get executed.

5.	What is hoisting in JavaScript?

Ans.
Hoisting in JavaScript refers to the behavior where variable and function declarations are moved to the top of their containing scope during the compilation phase. This means you can use variables and functions before they are declared in the code.

6.	Explain lexical scope

Ans. 
Lexical scope is the scope of a variable or function defined by its position in the source code. This scope is determined at compile time and remains consistent throughout the program’s execution.

7.	What is scope chaining?

Ans.
Scope chaining in JavaScript refers to the mechanism by which the JavaScript engine resolves variable names in nested functions. When a variable is accessed, JavaScript first looks for it in the current scope. If it doesn’t find the variable there, it moves up to the next outer scope, continuing this process until it either finds the variable or reaches the global scope.

8.	Explain closure.

Ans.
A closure in JavaScript is a powerful feature where a function retains access to its lexical scope, even when the function is executed outside that scope. Essentially, a closure is created when a function is defined inside another function, allowing the inner function to access the outer function’s variables.

9.	What is the difference between undefined and not defined in javascript

Ans.
* Undefined:
A variable is declared but not assigned a value.
* Not Defined:
A variable is not declared at all in the current scope.

10.	Explain spread and rest operator.

Ans. 
The spread and rest operators in JavaScript both use the same syntax: three dots (...). However, they serve different purposes depending on the context in which they are used.

* Spread Operator
The spread operator is used to expand elements of an iterable (like an array or a string) into individual elements. It’s commonly used in function calls, array literals, and object literals.

* Rest Operator
The rest operator is used to collect multiple elements and condense them into a single array. It’s typically used in function parameters to handle an indefinite number of arguments.


11.	Explain ‘this’ keyword in Javascript.

Ans.
In JavaScript, this keyword refers to the object that is currently executing a function or method. Its value is determined by how a function is called. this typically represents the context in which a function operates, allowing access to the properties and methods of its containing object.

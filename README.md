# Javascript (codeacademy)
https://www.codecademy.com/courses/introduction-to-javascript/lessons/introduction-to-javascript/exercises/introhttps://www.codecademy.com/courses/introduction-to-javascript/lessons/introduction-to-javascript/exercises/intro

1. A single line comment will comment out a single line and is denoted with two forward slashes // preceding it.
2. A multi-line comment will comment out multiple lines and is denoted with /* to begin the comment, and */ to end the comment. 
3. data types- number, string, boolean, null, undefined, symbol, object
eg: console.log('JavaScript');
console.log(2011);
console.log('Woohoo! I love to code! #codecademy');
console.log(20.49)
4. Arithmetic operators :
Add: +
Subtract: -
Multiply: *
Divide: /
Remainder: %
eg: console.log(21 + 3.5);
console.log(2022-1969);
console.log(65/240);
console.log(0.2708 * 100);
5. String concatination :
process of appending one string to another is called concatenation. 
6. Properties :
When you introduce a new piece of data into a JavaScript program, the browser saves it as an instance of the data type. All data types have access to specific properties that are passed down to each instance.
eg : console.log('Teaching the world how to code'.length);
    length= 30
7. Methods : Remember that methods are actions we can perform. Data types have access to specific methods that allow us to handle instances of that data type. JavaScript provides a number of string methods.

We call, or use, these methods by appending an instance with:

a period (the dot operator)
the name of the method
opening and closing parentheses
eg: console.log('Codecademy'.toUpperCase());
console.log('    Remove whitespace   '.trim());

8. Built-in Objects : In addition to console, there are other objects built into JavaScript. Down the line, you’ll build your own objects, but for now these “built-in” objects are full of useful functionality.

For example, if you wanted to perform more complex mathematical operations than arithmetic, JavaScript has the built-in Math object.

The great thing about objects is that they have methods! 
eg : console.log(Math.floor(Math.random() * 100));
console.log(Math.ceil(43.8));
console.log(Number.isInteger(2017));

9.Variables : variables label and store data in memory. There are only a few things you can do with variables:

Create a variable with a descriptive name.
Store or update information stored in a variable.
Reference or “get” information stored in a variable.
Creating a variable- eg: 
var favoriteFood = 'pizza';
var numOfSlices = 8;
console.log(favoriteFood);
console.log(numOfSlices);
output : pizza
8

10. Conditional Statement :
 A conditional statement checks a specific condition(s) and performs a task based on the condition(s).

In this lesson, we will explore how programs make decisions by evaluating conditions and introduce logic into our code!

We’ll be covering the following concepts:

if, else if, and else statements
comparison operators
logical operators
truthy vs falsy values
ternary operators
switch statement

11. If else staements :
eg: let sale = true;

sale = false;

if (sale) {
  console.log('Time to buy!');
} else {
  console.log('Time to wait for a sale.')
}

12. comparison operators :
eg : let hungerLevel = 7;
if (hungerLevel > 7){
  console.log('Time to eat!');
} else {
  console.log('We can eat later!');
};

13.  Functions : A function is a reusable block of code that groups together a sequence of statements to perform a specific task.

14. Function declaration :  a function declaration binds a function to a name, or an identifier. 
15.  Calling a function : a function declaration does not ask the code inside the function body to run, it just declares the existence of the function. The code inside a function body runs, or executes, only when the function is called.

To call a function in your code, you type the function name followed by parentheses.
16. Parameters and arguements : Parameters allow functions to accept input(s) and perform a task using the input(s). We use parameters as placeholders for information that will be passed to the function when it is called.
 The values that are passed to the function when it is called are called arguments. Arguments can be passed to the function as values or variables.
 eg : function sayThanks(name) {
  console.log('Thank you for your purchase ' + name + '! We appreciate your business.');
}
sayThanks('Cole');

17. Return : To pass back information from the function call, we use a return statement. To create a return statement, we use the return keyword followed by the value that we wish to return.
eg : function monitorCount(rows, columns) {
  return rows * columns;
}
const numOfMonitors = monitorCount(5, 4);
console.log(numOfMonitors);
18. Helper functions : We can also use the return value of a function inside another function. These functions being called within another function are often referred to as helper functions. 
eg : function monitorCount(rows, columns) {
  return rows * columns;
}
function costOfMonitors(rows, columns) {
  return monitorCount(rows, columns) * 200
}
const totalCost = costOfMonitors(5, 4);
console.log(totalCost);
19. Function Expressions :  In a function expression, the function name is usually omitted. A function with no name is called an anonymous function. A function expression is often stored in a variable in order to refer to it.
eg : const plantNeedsWater = function(day, plantNeedsWater) {
  if (day === 'Wednesday'){
     return true;
  }
 else {
   return false;
 }
 plantNeedsWater('Tuesday');
}
console.log(plantNeedsWater('Tuesday'));

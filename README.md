

#### 1) What is the difference between var, let, and const?

Difference between var, let, and const:
var is function-scoped, can be redeclared and updated.
let is block-scoped, can be updated but not redeclared.
const is block-scoped, cannot be updated or redeclared, must be initialized.

#### 2) What is the difference between map(), forEach(), and filter()? 

Difference between map(), forEach(), and filter():
map() returns a new array, does not change the original array.
forEach() executes a function for each element, returns undefined.
filter() returns a new array with elements that satisfy a condition.

#### 3) What are arrow functions in ES6?

Arrow functions in ES6:
Arrow functions are a shorter syntax for writing functions.
Example: const add = (a, b) => a + b;
They use lexical this and can be written in a single line.

#### 4) How does destructuring assignment work in ES6?

Destructuring assignment in ES6:
Destructuring allows unpacking values from arrays or objects into variables.
Example:
Array: const [a, b] = [1, 2];
Object: const {name, age} = {name: "Ifrat", age: 18};

#### 5) Explain template literals in ES6. How are they different from string concatenation?

Template literals in ES6:
Template literals use backticks ` and allow embedding variables with ${}.
They support multi-line strings.
Example: const msg = My name is ${name};
They are more readable than string concatenation like "My name is " + name.
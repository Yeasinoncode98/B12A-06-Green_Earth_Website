

1) What is the difference between var, let, and const?
==>

i.var is the old way and works within functions,

ii.let is for variables that can change inside a block.
 
iii.const is for values you don’t want to change.

2) What is the difference between map(), forEach(), and filter()?

==> 1.forEach is a loop that mainly used to write arrow function easily during scripting 
2.map() helps and  creates a new array by transforming items
3.filter() makes a new array with only the items that match a condition.Takes that is matched with its condition

3) What are arrow functions in ES6?
==>Arrow functions in ES6 are a shorter way to write functions — they don’t need the function keyword, use =>, and don’t have their own this, which makes them handy for callbacks and cleaner code.

4) How does destructuring assignment work in ES6?

==> Destructuring in ES6 lets you quickly pull values from arrays or properties from objects
we can take values easily declaring varibales anad its very faster ,efficient for programming 
like ==>

const numbers = [10, 20, 30];
const [first, second] = numbers;


5) Explain template literals in ES6. How are they different from string concatenation?

==>Template literals in ES6 let you create strings easily using backticks ` and ${} to insert variables or expressions.Using back tick we can easily write anything inside js and it is more easy to use template strings.It is written like 


like ==>

const name = "Yeasin";
const greeting = `Hello, ${name}!
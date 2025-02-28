1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
```
let percentage = function (marks,total)=>return(marks*100/total);

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```
let percentage = unction percentage(marks, total) {
  return (marks * 100) / total;
}
```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
}
```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
Function Expresioon
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
Function Expression
```js
let percentage = (marks, total) => (marks * 100) / total;
```
Function Expression


3. Why is a function definition an expression in JavaScript? Give one example of function expression.
Expression is something that results into a value 
Different ypes of values are number string undefined 
When we define a function ()
because funciton is an object object is a value 
Fucnation is an expression 
Herere we are storing an object ina value
Function is an obejct and that's the reason it is said function expression

4. Why is a function call an expression in JavaScript?

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Valid 5
five = add; // Valid 
five = five(10, 11); // Valid 21
five = function () {
  return 'Hello';
}; // Valid 
```
6. What is the difference between function definition and function call? Explain with an example.
Function definition is when we define a function

7. What is the similarities between function definition and function call?
We have talked about function defintion is an expresssion
Why? Function is an ovject 
Funciton call is also expression
REason is that function call always returns a value
IF it doesn't have a retur n statement it return undefiendd
Here we are treating hello as object 
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}
Function internally is an object 
Internally function is an object 
hello.user = 'Sam'; // valid or invalid
```

9. What is higher order function explain with an example.
HOF is an function that accepts funcitondefinition 
Add(cb)
Add is a higher order funciton
Funciton main()
Return main 
 
!.. which accepts a function definition  function lo cb function ni define cheyatam
2. whch returna funciton definciton funciton lopala inko function

10. Explain what is callback function. Why you can pass a function inside a function?
So, we talked about earlier that a callback function is afunction 
as an argument we can pass an expression and fgunciton is a nexpreissiom 
we can pass function nside another fucntion

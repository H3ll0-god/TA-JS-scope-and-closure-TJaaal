1. What does thread of execution means in JavaScript?
Here we have 6 line of code 

THread of exection is executing the code one after another
2. Where the JavaScript code gets executed?
in everybrowzer 
there is a thing known as Javascript engine
context menas 
3. What does context means in Global Execution Context?
Environment where code is getting executed
CONTEXT IS AN ENVIRONEMNT
4. When do you create a global execution context.
GLOBAL EXECUTION CONTEXT IS CREATED whenever the code is created for the first time 
5. Execution context consists of what all things?
EXECUTION context consists of 2 parts like daALF

6. What are the different types of execution context?
2 types
GLOBAL EXECUTION CONTEXT
FUNCTIONN EXECUTION CONTEXT
7. When global and function execution context gets created?
GLOBAL EXECUTION GETS CREATED WHENEVER you are executing in the start 
FUNCTION CREATED WHNEVER WE ARE EEXECUTIONG whenever you are executing in any function

8. Function execution gets created during function execution or while declaring a function.
when we are executing the function 

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.

 

```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)
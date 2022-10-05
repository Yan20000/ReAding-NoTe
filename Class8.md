save all of these in app.js for your website, you will 

function myFunction(){

console.log("Hello World!");

}

myFunction();

function sayHello(yourName){


    console.log("Hello, and wlcome" + yourName);

}
sayHello("Kassie");
sayHello("Jennifer");
sayHello("Micky Mouse");
----------

Reading Assignment Loops and operators:
 
 1. Comparison operators: 
compares its operands and returns a logical value based on if comparison is true. The operands can be number, string, logical or object values. for example === and !== operators. 


 1. Assignment operators:

 assignment operator assigns a value to its left operand based on the value on the right operand. The simple assignment operator is equal(=)which assigns the value of its right value of f() to the x. [read more](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)

 Loops:

 1. For statement
it's for loos simlar to Java and c for loop, 

for examle for ([initialExpression];[conditionExpression];[incrementExpression])
statement run by initialExpression is executed, conditionExpression expression is evaluated and statement executes , to update expression use incrementExpression is executed. 

 1. while statement //only while loops
is statemewnt executes its statements as long as specific condition evaluates to true. a while statement example:

while (condition)
statement

if condition becomes a false, statement within the loop stops excuting and control passes to the statement following loop. example 

The following while loop iterates as long as n is less than 3:

let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}
Copy to Clipboard
With each iteration, the loop increments n and adds that value to x. Therefore, x and n take on the following values:

After the first pass: n = 1 and x = 1
After the second pass: n = 2 and x = 3
After the third pass: n = 3 and x = 6

after the 3rd pass, the condition of n<3 is no longer true, so the loop terminates. 

---------

while loop can run through more than 50 times, for example empty the dish washer.generally we don't know ahead of time how many loop we want. but we want to keep asking the same questions until we get it right. The structure will start with 

while (condition to evaluate is true){execute this code}

let response = prompt("what's my fav color?");
while (response !=='yello'){

response = prompt("Wrong!, guess again.")
}

<!-- this is while loop, start at 0 so it can look  -->
while (true){

    console.log(i);
    i++;
}
# Javascript-Reto-7-dias

Reto de 7 dias en Java script  de www.hackerrank.com

Here is a rough breakdown of the topics covered in this series:

Day 1: Learn basic Input/Output, print "Hello World!", and get started with conditional logic.

Day 2: Introducing variables, arithmetic operators, switch statements, and objects.

Day 3: Learn more about objects and arrays.

Day 4: Learn some data types and features of ES6.

Day 5: Learn more ES6 features. ES6 is a certain set of enhancements to the original JavaScript keywords.

Day 6: Solve simple problems with algorithms, data structures, and recursion.

Day 7: Generate ASCII Art using JavaScript.

JavaScript is a high level, dynamic, interpreted programming language. Along with HTML and CSS, it's one of the three essential technologies used in Web content production. The majority of websites employ JavaScript, and it's supported by all modern web browsers without plugins.

----------------------
Day 1: Print The Inputlocked
Use what you learned in the previous challenge to complete the  function by printing the  parameter to the console.
Input Format
The first and only line of input contains a string.

Constraints
String length <=500

Sample Input
How many chickens does it take to cross the road?

Sample Output
How many chickens does it take to cross the road?

--------

Day 2: Introducing Arithmetic Operators

Here is the list of JavaScript arithmetic operators:

+  : Addition
-  : Subtraction
*  : Multiplication
/  : Division
%  : Modulus
++ : Increment
-- : Decrement
The order of precedence of arithmetic operators from high to low follows:

++, --
*, /, %
+, -


Addition

SAMPLE CODE

var a = 1;
var b = 2;

var ans = a + b;

console.log(ans);
OUTPUT

3
Subtraction

SAMPLE CODE

var a = 1;
var b = 2;

var ans = a - b;

console.log(ans);
OUTPUT

-1
Multiplication

SAMPLE CODE

var a = 3;
var b = 2;

var ans = a * b;

console.log(ans);
OUTPUT

6
Division

SAMPLE CODE

var a = 3;
var b = 2;

var ans = a / b;

console.log(ans);
OUTPUT

1.5
Modulus

SAMPLE CODE

var a = 3;
var b = 2;

var ans = a % b;

console.log(ans);
OUTPUT

1
Increment
The increment operator has 2  forms:

Preincrement: The increment operator is prefixed to a variable, and it ensures that the variable's value will be incremented by 1 before it is used.
Postincrement: The increment operator is postfixed to a variable, and it ensures that the variable's value will be incremented by 1 after it is used.
SAMPLE CODE

var a = 3; 

// preincrement: 'a' is incremented before being assigned to 'ans' 
var ans = ++a; 
// postincrement: 'ans' is not incremented until after the line is printed.
console.log(ans++); 
console.log(ans);
OUTPUT

4
5
Decrement
The decrement operator has  forms:

Predecrement: The decrement operator is prefixed to a variable, and it ensures that the variable's value will be decremented by 1 before it is used.
Postdecrement: The decrement operator is postfixed to a variable, and it ensures that the variable's value will be decremented by 1 after it is used.
SAMPLE CODE

var a = 3; 
// predecrement: 'a' is decremented before being assigned to 'ans' 
var ans = --a; 

// postdecrement: 'ans' is not decremented until after the line is printed.
console.log(ans--); 
console.log(ans);
OUTPUT

2
1
Task

Given two numeric variables, a and b, write the following:

Create a variable, add , and assign it the sum of  and .
Create a variable, sub, and assign it result of  subtracted from .
Create a variable,mul , and assign it the product of  and .
Create a variable,div , and assign it the result of of  divided by .
Create a variable, inc, and assign it the preincremented value of .
Create a variable,dec, and assign it the predecremented value of .
Note: Do not create variables a  and b. They have already been declared and initialized by our hidden code checker.

------------
JavaScript Objects

Objects are variables too, but objects can contain many values.

For example, this code below assigns three values (Fiat, 500, white) to a variable named myObject:

var myObject = {type:"Fiat", model:500, color:"white"};
The values are written as name:value pairs. The name and value are separated by a colon. The name:values
pairs (in JavaScript objects) are called properties.

Accessing Object Properties

You can access object properties in two ways:

objectName.propertyName
or

objectName["propertyName"]
Task

In this example, you are given a single line consisting of property type values of a car in the following order:

TypeName ModelName ColorName
These values are assigned to an object car that has the properties type, model and color (read the code in the editor carefully to learn how that is done). Your task is to complete the code to print the object.

Sample Input

Fiat 500 White
Sample Output

{ type: 'Fiat', model: '500', color: 'White' }

--------------------------------

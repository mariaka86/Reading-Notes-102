# Reading 07 notes
-control flow is the order that that computer executes statements (order of execution)
- function names have the same rules as variables.
- for a function to be executed the code has to be inside curly braces {}
- function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
-parameters are listed in the parantheses
-parameters are also knows as arguments
-arguments are the values received by the function

## why are functions used
- because you can reuse code that you only have to define one time
- you can use the same code many times with different arguments for varied results.
 **example
 
  function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);
-functions can be used the same way as variables like storing return values
**example 

let x = toCelsius(77);
let text = "The temperature is " + x + " Celsius";
the **assignment operator(=) assigns a value to a variable

let x=10;
**addition operator adds numbers

let x=6;
let y=5;
let z = x + y;
*same with the multiplication operator*
**Operator	Description
+	Addition
-	Subtraction
*	Multiplication
**	Exponentiation (ES2016)
/	Division
%	Modulus (Division Remainder)
++	Increment
--	Decrement
number + string= string
## JavaScript Comparison Operators
**Operator	Description

==	equal to

===	equal value and equal type

!=	not equal

!==	not equal value or not equal type

  >	greater than

  <	less than

>=	greater than or equal to

<=	less than or equal to

?	ternary operator


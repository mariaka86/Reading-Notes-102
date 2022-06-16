# Reading-08 notes
## Comparison Operators
- == and !== operators perform strictly equality and inequality comparisons 
- == Equal
- ==! Not equal
- === strictly equal
- !== strictly not equal
## Assignment Operators
- assign values to it's left operand based on it's right operand

- a simple assignment operand is =

- x = f() is an expression that assigns f() to x

- Addition Assignment x + = f() ---> x = x+f()

- Subtraction Assigment  x - = f() ----> x = x-f() 

- left shift assignment x << = f()

## Loops

* for statements

- for loops repeat until a condition is found false 

- for loops for JS, J and C are similar to each other

* for statement example
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

* for loop execution

- initialization expression - can declare variables and initializes loop counters

- Expression- evaluates if conditionExpression is true if it is, it execution otherwise it terminates the loop with for

- Execution- statement executes.

* While statements
 - only executes if specified condition evaluates to true
 ** example **
- while (condition)
  statement
 - let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}

- while loop executes as long as n is less than 3
- With each loop, the loop increments n and adds that value to x. so, x and n take on the following values:

After the first pass: n = 1 and x = 1
After the second pass: n = 2 and x = 3
After the third pass: n = 3 and x = 6
- After completing the third pass, the condition n < 3 is no longer true, so the loop terminates.

- if condition becomes false loop stops executing, control passes to statement after while loop



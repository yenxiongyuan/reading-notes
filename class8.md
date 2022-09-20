# Read: 08 - Operators and Loops

## What is Expression in Javascript?

In programming, an expression is something that returns a usable output value. 

## Comparison Operators:

* `== is true if the operands are equal`
* `!= is true if the operands are NOT equal`
* `=== is true if operands are equal and of the same type`
* `!== true if the operands are of the same type but not equal`
* `> greater than`
* `>= greater than or equal`
* `< less than`
* `<= less than or equal`

## Assignment Operator:

* assigns a value to a variable.
* let x = 8;
* const y = 9;

## For Statement

For loop will continually run until the condition becomes false.

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

for (let i = 0; i < 5; i++) {
  return ‘Your message here’;
}

## While Statement

While loop will executes its statement as long as it evaluates to true
while (condition)
  statement

The following example uses the while statement to output the odd numbers between 1 and 10 to the console:
let count = 1;
while (count < 10) {
    console.log(count);
    count +=2;
}

Output: 1, 3, 5, 7, 9


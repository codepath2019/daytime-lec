**check:** How can computer programs operate on complex data such as images, sound, color, letters, and numbers when all it understands is the binary system `010000011111111`?
- By mapping human data to binary

**check:** What is a binary number? Why do we as programmers care about binary systems?

**check:** In your own words, describe each of the following to your friend or your pet.
- what is a value is in JavaScript.
- What is a type?
- What is the difference between value and type if any?
- What is an expression?
    - An expression is any valid unit of code that resolves to a value.
- What is an operator?
- What is an operand?
- What is the difference between a unary operator and a binary operator?

>>> 1 / 5

>>> 1 % 5

>>> 6 % 1

>>> (6 % 9) / 3

>>> 1 * 3 + 2

>>> 3 + 2 * 3

>>> (3 + 2) * 3

**check:** What does `typeof` operator do? What kind of operator is `typeof`?

**check:** What do you think `typeof` is used for? Do some research online and you may find some interesting applications!

>>> `typeof 4.5`

>>> `typeof undefined`

>>> `typeof "123"`

>>> `typeof true`

**check:** What is a comparison operator? What is it used for?
- Comparison operators are used in logical statements to determine equality or difference between variables or values.

**check:** What are some ways to produce boolean values?
- using comparison operators to compare
    - strings
    - numbers
**check:** What is this `==` symbol? How many arguments does it take? What is its output?
**check:** What is this `===` symbol? How many arguments does it take? What is its output?
**check:** What is the main difference between `==`, and `===`?

**check:** What does it mean for a value to be truthy or falsy? Give examples of all falsy values.

**check:** What is a logical operator?
- Logical operators are used to determine the logic between variables or values.
- Logic is applied to boolean values. So logical operators interact with boolean values, and values that can be converted into boolean values.

**check:** What are the three types of logical operators?

>>> true && true

>>> true && false

>>> false && true

>>> false && false

>>> true || true

>>> true || false

>>> false || false

>>> false || true

>>> !false

>>> !true

>>> !9

>>> !0

>>>!!false

>>> !!true



##short circuiting with &&, ||
`||`: returns the value to its left when that can be converted to true and will return the value on its right otherwise.

**tip in explanation**: keep evaluating each value until you either discover the first value that is evaluted to true, return that, or return the last value in the chain of statements

>>> true || true

>>> 3 || true

>>> undefined || 3

>>> 0 || false

>>> false || 0

>>> undefined || undefined || 0 || false || 3 || false


`&&`: When the value to its left is something that converts to false, it returns that value, and otherwise it returns the value on its right.

**tip in explanation**: keep evaluating each value until you either discover the first value that is evaluted to false, return that value, or return the last value in the chain of statements

>>> true && true

>>> true && false

>>> true && 13

>>> false && 3

>>> false && null

>>> null && true

>>> true && true && true && true && false


##Helpful resources:
- https://www.w3schools.com/js/js_comparisons.asp
- [Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [JavaScript Expressions and Statements](https://medium.com/launch-school/javascript-expressions-and-statements-4d32ac9c0e74)

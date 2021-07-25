# Expressions and operators

- Operators

**The conditional operator is a particular ternary operator in JavaScript that has both binary and unary operators. Two operands are required for a binary operator, one before and one after the operator:**

**For example,** `3+4` **or** `x*y` **.**

**A single operand, either before or after the operator, is required for a unary operator:**

**For example,** `x++` **or** `++x` **.**

* Assignment operators

**Based on the value of its right operand, an assignment operator assigns a value to its left operand. Equal (=) is a simple assignment operator that assigns the value of its right operand to the left operand. x = y, in other words, assigns the value of y to x.**

**For more information:** [Assignment operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)


* Return value and chaining

**Assignments like x = y, like most expressions, have a return value. It may be accessed by assigning or logging the expression:**

> `const z = (x = y);`

> `console.log(z);`

> `console.log(x = y);`

- Comparison operators

**A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values.**

> `var var1 = 3;`

> `var var2 = 4;`

### Comparison operators

| Operator	 | Examples returning true |
| --- | ----------- |
| Equal (==) | 3 == var1 |
| Not equal (!=) | var1 != 4 |
| Greater than (>) | var2 > var1 |
| Greater than or equal (>=) | var2 >= var1 |
| Less than (<) | var1 < var2 |
| Less than or equal (<=) | var1 <= var2 |


- Arithmetic operators

**The standard arithmetic operations (+, -, *, /)**

### Arithmetic operators

| Operator	 | Example |
| ------------   | -------- |
| Remainder (%)   | 12 % 5 returns 2 |
| Increment (++)   | If x is 3, then ++x sets x to 4 and returns 4, whereas x++ returns 3 and, only then, sets x to 4. |
| More  | [Arithmetic operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#arithmetic_operators) |


- Bitwise operators


### Bitwise operators

| Operator	 | Usage |
| --- | ----------- |
| Bitwise AND | `a & b`	 |
| Bitwise OR | `a | b` |
| Bitwise XOR | `a ^ b` |
| Bitwise NOT | `~ a` |


- Logical operators

### Logical operators

| Operator	 | Usage |
| --- | ----------- |
| `Logical AND (&&)` | `expr1 && expr2	`	 |
| `Logical OR (||)` | `expr1 || expr2` |
| `Logical NOT (!)` | `	!expr` |


# Loops and iteration

## for statement:

**A for loop repeats until a specified condition evaluates to false.**

**Example 1**

> `for ([initialExpression]; [conditionExpression]; [incrementExpression])`

**Example 2**

> `for (let step = 0; step < 5; step++) {`

` console.log('Walking east one step');`

> `}`


## do...while statement:

**The do...while statement repeats until a specified condition evaluates to false.**



**Example**

`do`

>  `statement`

`while (condition);`

## while statemen:

**A while statement executes its statements as long as a specified condition evaluates to true.**

`while (condition)`
>  `statement`

## labeled statement

**A label provides a statement with an identifier that lets you refer to it elsewhere in your program.**

`label :`
> `statement`


## break statement:

**Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.**

`break;`

`break [label];`

## continue statement:

**The continue statement can be used to restart a while, do-while, for, or label statement.**

`continue [label];`


## for...in statement:

**The for...in statement iterates a specified variable over all the enumerable properties of an object.**

`for (variable in object)`
>  `statement`


## for...of statement:

**The for...of statement creates a loop Iterating over iterable objects**

`for (variable of object)`
>  `statement`

# Reference

+ [Expressions and operators
](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
+ [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
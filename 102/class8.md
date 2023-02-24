# Expressions and Operators

## High Level

**At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.**

+ The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.
+ All complex expressions are joined by operators, such as + and =
+ The precedence of operators determines the order they are applied when evaluating an expression. For example the * takes precadence over + in an expression. Parentheses can override which creates a grouped expression.
+ JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator
+ ++ and -- are the only postfix operators in JavaScript — all other operators, like !, typeof, etc. are prefix.

## Assignment Operators

**An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.**

## Comparison Operators

+ A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numberical, string, logical, or object values.

## Loops

- Loops offer a quick and easy way to do something repeatedly. They all essentially do the same thing, repeat an action some number of times. It's possible for the number to be zero.
- The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

### For Statement

- A for loop repeats until a specified condition evaluates to false.
- Looks like this:

> for (initialization; condition; afterthought)
  statement

This is happening:

1. The initializing expression initialization, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.

2. The condition expression is evaluated. If the value of condition is true, the loop statements execute. Otherwise, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)

3. The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.

4. If present, the update expression afterthought is executed.

5. Control returns to Step 2.

### While Statement

- A while statement executes its statements as long as a specified condition evaluates to true.

while (condition)
    statement

- If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
- The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.
- Avoid infinite loops. Make sure the condition in a loop eventually becomes false—otherwise, the loop will never terminate! The statements in the following while loop execute forever because the condition never becomes false:

// Infinite loops are bad!
while (true) {
  console.log("Hello, world!");
}
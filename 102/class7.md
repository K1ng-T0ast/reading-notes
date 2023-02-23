# Programming with Javascript

## Control Flow

- First to last unless computer runs across structures that change the control flow such as conditionals and loops
- Control structures can dictate complex flows of processing with only a few lines of code

## JavaScript Functions

- A block of code designed to perform a particular task, is excecuted when something invokes or calls it

### JS Function Syntax

- Defined with the function keyword, followed by a name, followed by parentheses
- Same rules as variables, digits letters underscores and dollar signs
- Parentheses may include parameter names separated by commas
- Execute code inside curly brackets
- Function parameters are listed inside the parentheses () in the function definition.
- Function arguments are the values received by the function when it is invoked.
- Inside the function, the arguments (the parameters) behave as local variables.

**Function Invocation and Return**

- Code inside will execute when something invokes such as an event user click, called from JS code, auto or self invoked
- When JS reaches a return statement, function will stop executing
- If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
- Functions often compute a return value. The return value is "returned" back to the "caller"

*You can reuse code, define it once and use it many times*

- Parentheses operator invokes the funtion

- Variables declared within a JavaScript function, become LOCAL to the function, so above and below code can not use function
- Local variables can only be accessed from within the function
- Local variables are created when a function starts, and deleted when the function is completed.

## JS Operators

There are different types of JavaScript operators:

- Arithmetic Operators, perform arithmetic on nyumbers
- Assignment Operators, assign values to JS variables
- Comparison Operators
- Logical Operators
- Conditional Operators
- Type Operators

> When used on strings, the + operator is called the concatenation operator

> If you add a number and a string, the result will be a string!

ex. let y = "5" + 5;     returns as 55

**Comparison Operators**

==	equal to
===	equal value and equal type
!=	not equal
!==	not equal value or not equal type
>	greater than
<	less than
>=	greater than or equal to
<=	less than or equal to
?	ternary operator

**Logical Operators**

&&	logical and
||	logical or
!	logical not

**Type Operators**

typeof	Returns the type of a variable
instanceof	Returns true if an object is an instance of an object type

**Bitwise Operators**

&	AND	5 & 1	0101 & 0001	0001	 1
|	OR	5 | 1	0101 | 0001	0101	 5
~	NOT	~ 5	 ~0101	1010	 10
^	XOR	5 ^ 1	0101 ^ 0001	0100	 4
<<	left shift	5 << 1	0101 << 1	1010	 10
>>	right shift	5 >> 1	0101 >> 1	0010	  2
>>>	unsigned right shift	5 >>> 1	0101 >>> 1	0010	  2

1. What is control flow?
   - order in which comp executes statements in script, first to last unless change is detected such as conditionals and loops
2. What is a JS function?
   - a block of code designed to perform a task and executed when something invokes it, calls it
3. What does it mean to invoke or call a function?
   - Code inside function will execute when an action or something calls or invokes the function such as event like a click, called from code, or self invoked automatically
4. What are parentheses for when you define a function?
   - it invokes the function, accessing a function without the parentheses will return the function object instead of the result
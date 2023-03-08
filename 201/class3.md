# Class Notes (Reading notes below in separate header)

**Arrays, operators, expressions, conditionals and loops are all pivotal in how we use data types together in JS and make sense of complex tasks using logic and lets us create tasks to help access these data types in various formats for the user to interact with**

## JS Data Types (primitives)

+ Strings = natural language characters, double or single quotes
  - Use the \ (escape) character to string together language if using all single quotes, so like using possessive
+ Boolean = true and false, yes or no, 1 and 0
+ Number = integers, fractions, doubles, any number
+ Null = represents the lack of value
+ Undefined = also the lack of value, but usually from something bad

### String examples

> let person = "jacob"
> let lovesToProgram = true
> typeof() if you want to know what data type something is in console

**How to Think about your code: 

## Conditional logic

+ if statement = lets you optionally run a line of code. Think detour
> if (expression){do whatever here}

+ if/else statement = Fork in the code road
> if (true){
    console.log('Route 1);
} else {
    console.log('Route 2');
}

+ if/else/if = optional detour that also has a fork in it
> if (true){
    console.log('option 1');
} else if (false){
    console.log('option 2');
}

+ switch = picks one or more lines of code to run, all based on a single expression
> switch (expression){
    case 'value1':
        console.log('value1!);
    case true:
        console.log('true!');
    case 1:
        console.log('number 1!');
    default:
        console.log('I do not know');
}

# HTML Lists, Control Flow with JS, and the CSS Box Model

## Ordered Lists and Unordered Lists

1. When should you use an unordered list in your HTML document?
   - Used for grouping a collection of items that do not have numerical ordering, the order is meaningless and thus should be used as such

2. How do you change the bullet style of unordered list items?
   - If compact, use the CSS property line height with a value of 80% or you can change the style using shapes or 'type + circle or disc or square or sometimes triangle'

3. When should you use and ordered list in your HTML document?
   - When you want a list of items with a preceding marker where the order matters

4. Describe two ways you can change the numbers on list items provided by an ordered list?
   - Using an element attribute such as reversed, whcih lists items in reverse order or..
   - Type followed by a for lowercase, A for uppercase, i for lowercase roman numerals, I for uppercase roman numerals

## The Box Model

1. Describe the CSS properties or margin and padding as characters in a story. What is their role in a story titled: "The Box Model"?
   - Padding was ambitious and loved the box it lived next to known as content. It lived right up against content's wall and built a fence right up against it and all around. One day, Padding wanted a better look at content so it moved the entire fence away from content. It was satisfied until one day padding's neighbor, margin, peeked over the fence and said, "Hello padding! I've noticed that you have a lovely fence but some of the other contents in the neighborhood are starting to feel cramped. Why don't you let me create more room around your fence so it doesn't feel so cramped around your box?" Padding was ecstatic and agreed for it did not know that was possible. 

2. List and describe the four parts of HTML elements box
   - Content box: area where content is displayed
   - Padding box: sits around the content as white space
   - Border box: wraps the content and any padding
   - Margin box: outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements

## Arrays, Operators and expressions, Conditionals, Loops

1. What data types can you store inside of an array?
   - Strings, numbers, objects, and other arrays

2. Is the people array a valid javaScript array? If so, how can I access the values stored? If not, why?
   - Yes because everything store in this array is a string, number or object and arrays inside each other.
   - You can access the values stored by using bracket notation and supplying the item's index, starting with 0 and moving up 1 each time in the array

3. List five shorthand operators for assignment in javascript and describe what they do
   - Assignment, x = f(): Used to assign a value to a variable. Evaluates to the assigned value.
   - Addition, x += f(): assigns the value of the right operand to a variable and assigns the result to the variable
   - Subtraction, x -= f(): Subtracts the value of the right operand from a variable and assigns the result to the variable
   - Logical AND, x &&= f(): only assigns if x is truthy
   - Logical OR, x |= f(): only assigns if x is falsy

4. I have no idea but my best guess would be nothing because the left operand inside the parentheses is evaluating first and then adding b which is a string.

5. Describe a real world example of when a conditional statement should be used in a JS program?
   - If you were to ask a series of questions on a personality test online and then given a certain result from the user inputs from each question that has multiple answers.

6. Give an example of when a loop would be useful in JavaScript
   - If you were to ask for a password to be inputted to access an account and the loop does not terminate until the conditions, this case a correct password, is met.


## Things I Want to know more about

**In an array when accessing values in a multidimensional array, how does that work with the example provided in this example below to find the third item**

>const random = ['tree', 795, [0, 1, 2]];
>random[2][2];


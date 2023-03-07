# Basics of HTML, CSS, and JS

**_HTML, CSS, and JavaScript are the 3 main building blocks of a website and essential for path learning into front end web development. Learning how something like a website is structured, organized, styled, and brought to life is key to wrapping concepts like functions and CSS styling, how those interact and behave, and how you could use them to accomplish anything you want in your site creation goals_**

1. Why is it important to use semantic elements in our HTML?
   - It gives meaning to our code or pieces of a code. In HTML a semantic element provides a role or meaning to the code so that the browser knows how to display it correctly. HTML should be coded to represent the data that will be populated. 

2. How many levels of heading are there in HTML?
   - There are 6 heading elements (h1 - h6) that each represent a different level of content in the document. Hierarched as main, sub, sub sub, and so on.

3. What are some uses for the <sup> and <sub> elements?
   - The sub tag defines subscript text that appears half a character below the normal line. Think chemical formulas. Sup is superscripted text that appears half a character above the normal text and can be used for footnotes.

4. When using the <abbr> element what attribute must be added to provide the full expansion of the term?
   - The title attribute followed by the definition in plain text and surrounded by quotes.


## Learn CSS

1. What are ways we can apply CSS to our HTML?
   - Either with an external stylesheet that is an external file with the .css extension, an internal style sheet which is located within the HTML doc itself contained inside the HTML <head>, and/or with inline styles which are CSS declarations that affect a single HTML element.

2. Why should we avoid using inline styles?
   - It is not best practice, it is the least efficient for maintenance, and makes HTML code more difficult to read and understand.

3. Review block of code:

>  h2 {
>     color: black;
>     padding: 5px;
>     }

   - What is representing the selector? H2
   - Wich components are the CSS declarations? Color, padding
   - Which components are considered properties? black, 5px


## Learn JS

1. What data type is a sequence of text enclosed in single quote marks?
   - A string

2. List 4 types of JavaScript operators
   - Addition +, adding two numbers together or combine two strings. 'hello ' + 'world!';
   - assignment =, assigns a value to a variable. let myVariable = 'Bob';
   - Strict equal ===, performes a test to see if two values are equal, returns a true false boolean result. let myVariable = 3; myVariable === 4; 
   - Not, does not equal !, !==, returns the lofically opposite balue of what it precedes. Turns true into false and when used alongside the equality operator, the negation operator tests whether two values are not equal.

3. Describe a real world problem that you could solve with a function
   - It could solve data validation in a web form, such as inputting and validating an e-mail address and checking to see if it has an @ symbol plus a domain name.

## Conditionals

1. An if statement checks a __ and if it evaluates to __ then the code block will execute
   - Condition to test, true

2. What is the use of else if?
   - Only runs if the if condition returns as false or not true. It is used when you want to run another code if an evaluation returns as false from the conditional statement and there is more than two outcomes.

3. List 3 different types of comparison operators
   - === and !== test if one value is identical to, or not identical to, another
   - < and > test if one value is less than or greater than another
   - <= and >= test if one value is less than or equal to, or greater than or equal to, another

4. What is the difference between the logical operator && and double |?
   - && AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.
   - Double | OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.


## Things I Want To Know More About

**_Ternary Operators_**

**_Switch Statements_**

**_More Examples of Nesting Conditional Statements_**
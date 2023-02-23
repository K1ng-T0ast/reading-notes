# Javscript

## Basic Output

We can distinguish 3 major parts of what we usually refer to as "JavaScript".

1. The language itself. This is fairly standard among the various environments, both in the various browsers and in the various server-side environments.

2. The DOM API - how the language can interact with the various parts of a web page while in the browser. While in this respect the various browsers are getting closer to each other they still differ. Several libraries, most prominently JQuery, is trying to provide a unified API.

3. The server API (or just API) provided by Node.js or one of the other server-side systems.

** You can embed or include the JavaScript code directly inside the HTML file using an external JS file or inline code by writing script in opening and closing tags

### Input Output

+ Alert, pop up in browser with the text)
> script language="javascript">
 
alert("Hello World");
 
/script>
 
+ document.write, change the content of the page often if one wanted to change what is already implemented
> First line
script>
 
document.write("<h1>Hello World</h1>");
 
/script>
Last line
 
+ console.log, shows debug info
> script>
 
console.log("Hello World");
 
/script>

**Data Types**

// string --> "text", "42" always in quotations marks
// numbers --> 42, 123, 456 separated by commas
// boolean --> true/false

A variable does not have quotes

**Input from a User**

+ Prompt isn't used widely but good to show how to interact with JS. All examples are with script opening and closing tags
  - Can type in something like 

  var name = prompt("your name:", ""); 
  document.write(Hello ", name);

+ Confirm asks the user to confrim an action and then a conditional reaction from the JS

if (confirm("Shall I print Hello World?")) {
    document.write("Hello World");
} else {
    document.write("OK, I won't print it.");

+ Funtions *must revisit*

function keyword followed by the name of the new function. Then list of parameters in parentheses and then a block of expressions in curly braces. EX.

function show() {
  console.log('Hello World');
}
 
console.log('before');
show();
console.log('after');

 the code is not executed in the order it can be found in the file. Although the function is declared before everything else, it is only executed later, when we call it using its name show();

** Variables

+ Variables are containers fore storing data or storing data values

var x = 5;
var y = 6;
var z = x + y;

other use cases are between the let and undeclared variables

**Always declare JS variables with var, let, or const**

Const is a general rule to always declare variables unless you think the value of the variable can change, which case use let. ex.

const price1 = 5;
const price2 = 6;
let total = price1 + price2;

const value cannot be changed but the let can

**All JS variables must be identified with unique names called identifiers**

The general rules for constructing names for variables (unique identifiers) are:

+ Names can contain letters, digits, underscores, and dollar signs.
+ Names must begin with a letter.
+ Names can also begin with $ and _ (but we will not use it in this tutorial).
+ Names are case sensitive (y and Y are different variables).
+ Reserved words (like JavaScript keywords) cannot be used as names.

**Javascript Data Types**

JavaScript variables can hold numbers like 100 and text values like "John Doe".

In programming, text values are called text strings.

JavaScript can handle many types of data, but for now, just think of numbers and strings.

Strings are written inside double or single quotes. Numbers are written without quotes.

If you put a number in quotes, it will be treated as a text string.

**Declaring a JS Variable**

Declare with var or let keyword

var carName;

has no value until we give it one like

carName = "Volvo";

or

let carName = "Volvo";

Many Variables

let person = "John Doe", carName = "Volvo", price = 200;

can also span multiple lines
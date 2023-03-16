# Class Notes

## API

**Aplication Programming Interface**

- DOM is an API for HTML elements in JS.
- Oven example, button knobs as the interface, specific roles - temp knobs, location of burner, etc. Oven door safely put things in and out of oven, door feature.
   - DOM has API - get element by ID as example

## HTML Form Elements

- Websites almost always include forms or getting input from the user.

1. Input: Text, numbers, radio buttons, checkboxes, etc.
2. Labels, field sets, legends: Meta data tags like, please input valid e-mail address, incorrect password, etc.
3. Form: a feature that the form inputs do. 

## Browser Events API

**Events: Anything a user does to interface with the page in any way**

# Reading Notes

## Troubleshooting JavaScript

1. Name some key differences between a Syntax Error and a Logic Error.
   - Spelling errors that cause the program to stop working as intended part or all the way.
   - Logic errors where syntax is correct but the code in not what is intended like associating the wrong function or variable. 

2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
   - There was a logic error in the cookie stand lab where I was appending the footer row that contained the totals for all stores and the grand total but wasn't appearing on the bottom of the table because of where I was invoking the function. Also in that same instance, another logic error popped up before where I accidentally auto filled the appending row to the incorrect position, effectively overwriting the previous row I had created because I had called it in using the same name.

3. How will this topic continue to influence your long term goals?
   - To try and have checkpoints througout the process to help identify which areas are problematic and need attention. Also to be more careful when constructing code and giving it a once over before moving on.

## The JS Debugger

1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
   - It's like learning a new song on an instrument, let's say a guitar, and it allows you to watch for variables and like you would sections in a song and see what is doing what. Breakpoints are like stopping before the bridge of a song or a certain section and before moving on to the next music section you stop and continue working on the first section until it's correct.

2. Define what a breakpoint is.
   - in the debugger window, the breakpoint is something you first set in your JS code and then in the window, the JS will stop executing at each breakpoint letting you examine JS values. After examining, you can resume code by hitting play.

3. What is the call stack?
   - The call stack section shows you what code was executed to get to the current line. In the debugger window.

## Things I want to know about

**_More tools to help you parse through your code and help you understand what is going on_**
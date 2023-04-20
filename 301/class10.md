# In Memory Storage

## JavaScript Call Stack

1. What is a ‘call’?

    The invocation of a function, typically one at a time from top to bottom. A Callstack is a data structure that uses the LIFO (last in first out)  principle to temporarilystore and manage function invocation.

2. How many ‘calls’ can happen at once?

    One at a time and synchronously

3. What does LIFO mean?

    Last in, First out

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack

    <img src="./assets/callstack.png" alt="example of call stack" title="Call Stack Example">

    (source: https://www.youtube.com/watch?v=2ZH_1d8TYVg)

5. What causes a Stack Overflow?

    A recursive function, one that calls itself, without an exit point.

## JavaScript Error Messages

1. What is a ‘reference error’?

    When a variable or function is used in code but has not been declared or defined in scope.

2. What is a ‘syntax error’?

    When code is not written according to rules of a programming language.

3. What is a ‘range error’?

    A value is not within an acceptable range like in an array.

4. What is a ‘type error’?

    A value is not of the expected data type.

5. What is a breakpoint?

    A point in the code where execution is paused so the dev can examine the state of the application.

6. What does the word ‘debugger’ do in your code?

    It brings up a tool to help find and fix errors in code line by line.
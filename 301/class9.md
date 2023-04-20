# Functional Programming

## Functional Programming Concepts

1. What is functional programming?

    A programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing state or mutable data.

2. What is a pure function and how do we know if something is a pure function?

    - It returns the same result if given the same arguments (also referred to as deterministic)
    - It does not cause any observable side effects

3. What are the benefits of a pure function?

    The code is easier to test and can unit test pure functions with different contexts.

4. What is immutability?

    Unchanging over time or unable to be changed. Re: data, its state cannot change after it's created. You have to create a new object with the new value.

5. What is Referential transparency?

    If a function consistenly yields the same result for the same input, it is referentially transparent. Pure functions + immutable data = referential transparency.

## Node JS Modules and require()

1. What is a module?

    A self contained unit of code that hold functionality and can be imported and used in other parts of a node js app.

2. What does the word require do?

    Built in function used to import modules or libraries into the current file.

3. How do we bring another module into the file the we are working in?

    Using CommonJS with require or ECMAScript(ES) with import

4. What do we have to do to make a module available?

    Either using module.exports or with export.


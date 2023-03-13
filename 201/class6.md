# Class 5 Lecture Notes (reading notes below)

## JS Objects

**Object Literals**

- An object created with curly brackets
- A data structure like an array. (A bucket that holds items in a specific index.) Instead of indices, objects use keys or key value pairs

**Objects vs Arrays**

- Object = one thing and able to give more detail to that one thing (name pikachu, type electric, ability thunderbolt)
- With an array we may have multiple variables that may not necessarily meet each other (let name = pikachu, let type = pikachu)

*Contextual This*

- Keyword that changes depending on where in the code you're calling it. Refers to the object that is surrounding the "this" keyword

*Bracket vs Dot Notation*

- 2 ways to refer to properties or keys on an object
- Dot notation uses the name of a property attached to the object (pokemon.name, pokemon.type)
- Bracket notation uses square brackets and reads from a string value(pokemon["actionPoints"])
  - Is an expression ex: let key = "actionPoints" , pokemon[key]
  - let us use variables as property names. Helpful when we want to read from a property that is a variable.

*Functions on objects are known as methods* gotta be called using a dot or a bracket

**DOM or document object model**

- Getting JS into the rendered HTML. Built in API.
- Creating HTML elements
- Read from already rendered HTML elements
- Update / remove elements

# Reading Notes 

## Javascript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?
    - Objects could be viewed as something like a car with certain specs, make, functionality, etc. Like Subaru Crosstrek and the related data being wheeltype AWD, MPG, etc. Just collection of related data etc.

2. What are some advantages to creating object literals?
    - You can see the objects contents written out instead of using classes to decode the meaning and sending one object with a collection of data is much easier than sending multiple items one at a time and trying to pull from an array is much harder when trying to identify individual items by name.

3. How do objects differ from arrays?
    - Object = one thing and able to give more detail to that one thing (name pikachu, type electric, ability thunderbolt)
    - With an array we may have multiple variables that may not necessarily meet each other (let name = pikachu, let type = pikachu)

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
    - When you want to access a value whos object name is held in a function. 

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

    const dog = {
    name: 'Spot',
    age: 2,
    color: 'white with black spots',
    humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
    }
    }

  - This is referring to the object name and age. Using this in this instance allows us to use the same method definition for every object we create, in this case name and age. Useful for multiple object literals and when using constructors.

## Introduction to the DOM

1. What is the DOM?
    - Document object model, a programming interface for web documents. Represents the page so that programs can change the document structure, style and content. Represents the document as nodes and objects so programming languages can interact with the page itself. It allows the browser window or HTML to be manipulated and can be modified using a scripting language like JS.

2. Briefly describe the relationship between the DOM and JavaScript.
    - Without the DOM, the JS language wouldn't have any idea or what to make of web pages, HTML, and their counterparts. DOM is not a scripting language but is the link between the HTML document and JS.

## Things I want to know More About

**_How to utilize objects together to provide information using sums or multiples of the objects_**
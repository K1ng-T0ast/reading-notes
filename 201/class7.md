# Object-Oriented Programming, HTML Tables

## Domain Modeling

1. Explain why we need domain modeling

   - It helps to understand the specific problem among stakeholders, much like a wireframe can tell a story and give structure to an idea. It can communicate the problem using understandable vocabulary by cross functional teams. Validates the problem within a coded construct.

## HTML Table Basics

1. Why should tables not be used for page layouts?
    
   - Reduces accessibility for visually impaired users, the output will be confusing for users because things like screen readers interpret HTML tags
   - A table will involve more complex markup structure and can be harder to write, maintain, and debug
   - Tables are sized according to their content by default which makes styling a difficult task

2. List and describe 3 different semantic HTML elements used in an HTML table.
   - td which is table data, the smallest container inside a table cell
   - tr which is table row and stops the table from growing so you can create a new row
   - th which are table headers that go at the start of a row or column and provide easy to see definitions for the type of data in that row

## Introducing Constructors

1. What is a constructor and what are some advantages to using it?

   - If you have more than one object and want to change properties of the object without affecting the others. Reusability, multiple instances of an object with the same properties and methods. 
   - Help to encapsulate the data or details of an object making it easier to maintain and manage
   - Can be used to create objects that have the same interface but may have different uses

2. How does the term this differ when used in an object literal versus when used in a constructor?

   - in object literals this can refer to an object that the method or variable is define

   - in constructors this is the new object that a constructor is initializing

## Object Prototypes Using a Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.

   - Prototypes are a way to share methods and properties between objects and inheritance is the ability of an object to inherit the methods and properties from another object. In the salmon cookie project, 5 stores with sales data for any given day were needed to be displayed for the company. The sales data was different across all 5 stores but the method the company wished us to calculate the sales data remained the same across the board so I created a prototype method from one store and let the other 4 stores inherit the method not only containing the work and minimizing the debugging but allowed fro greater flexibility should the needs of the business change.

## Things I want to know more about

**_A real world example of how constructors can assist with complex asks/domain modeling_**
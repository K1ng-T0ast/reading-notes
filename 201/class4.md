# Class 3 Lecture Notes (reading notes below)

## Arrays (non primitives)

- Designed to put structure around primitives, containers for multiple values, holds any type
  - Organized by an index number (0, 1, 2, 3, etc)
  - Represents the distance traveled in the index, not the position
  - mutable (mutated?) it changes dynamically
  - Push and pop adds and removes values to the end
  - Use unshift and shift to add and remove from the front

> let people = ["Jacob"] >> returns as Jacob
> people.push('JB') >> returns as 2
> people[0] >> returns as Jacob
> let lastPerson = people.pop()

## Loops

- Looping code, any time you want to repeat lines of code more than once
- Handy at reading all values individually from an array
- Allows our code to be dynamic

**For loop, while loop, do while loop**

### For Loop

- 3 parts to the parentheticals. Initializer; condition; increment the initializer
> for (let i = 0; i < 5; i++) >> runs 5 times because it's starting at 0 and running until less than 5

- Apply to arrays:

> for (let i = 0; i < people.length; i++)
console.log(people[i]);

### While Loop

> while (condition) is true line of code will run

# Class 4 Readings

**CSS Layout is just as important to learn as the JS that guides it. It can make your efforts in coding realistic and noteworthy as you're learning complex lines of code, giving practicality and humanity to what you're trying to execute. Functions are a way to give us even more control over our current project which is an about me website**

## Creating Hyperlinks

1. To create a basic link we wrap text or other content inside what element?
  - the a element

2. The href attribute contains what information?
  - known as the hypertex reference or target, it contains the web address

3. What are some ways we can ensure links on our pages are accessible to all readers?
  - good link text
  - don't repeat the URL as part of the link text
  - don't say link or links to in the link text
  - keep your link text as short as possible
  - minimize instances where multiple copies of the same text are linked to different places

## CSS Layout

1. What is meant by "normal flow"?
  - elements on a webpage lay out in a normal flow if you haven't applied any CSS to change the way they behave. It ensures your content is readable even if the user is using a very limited browser. It is a good starting point to change how elements behave.

2. What are a few difference between block level and inline elements?
  - block level fills the available inline space of the parent element containing it and the element grows along the block dimension to accommodate. 
  - Inline is just the size of the content within the block. Cannot change certain parameters except on images.

3. ___ positioning is the default for every HTML element
  - Static positioning

4. Name a few advantages to using absolute positioning on an element
  - You can create isolated UI features that don't interfere with the layout of other elements on the page. You can place the element anywhere on the screen and would not have to adjust parameters based on the positioning of other elements.

5. What is the key difference between fixed and absolute positioning?
  - Absolute fixes and element in place relative to its nearest positioned ancestor or intial containing block and fixed fixes an element in place relative to the visible portion of the viewport.

## Functions

1. Describe the difference between a function declaration and a function invocation.
  - Declaration is creating a function. Invoking it is actually running the function.

2. What is the difference between a parameter and an argument?
  - A parameter is whats needed inside the function parentheses in order to do its job properly. The values that are declared within a function when a function is called is an argument. Variables that are defined when the function is declared is a parameter.

## Pair Programming

1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.
  - Greater efficiency: having two sets of eyes on code is highly beneficial and can help you catch mistakes, learn from those mistakes, ideation on a solution, and enjoyability. Already had practice with this and can vouch for all these benefits. This helps the learning process much less of a chore and therefore invoking the ability to be better, faster.

2. Job Interview readiness: Being able to share and review code with someone more experienced not only helps to prepare you for the difficulty of an interview and/or the job you're applying to, but it also helps to set the proper mental expectations for yourself. You can also speak to this prep to show how good of a collaborator you can be.

## Things I want to learn more about

**_Creating functions within arrays_**

**_Faster ways to think about CSS styling process that works more from the creative end rather than functional_**
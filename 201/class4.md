# Class 3 Lecture Notes

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
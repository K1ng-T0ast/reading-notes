# Passing Functions as Props

## Lists and Keys

1. What does .map() return?

    A new array that contains the results of applying the given function to each element in the original array without modifying/mutating. 

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

    Using curly braces inside of an element.

3. Each list item needs a unique ____.

    Key

4. What is the purpose of a key?

    Helps React to identify items that have changed, have been modified, or removed.

## The Spread Operator

1. What is the spread operator?

    It is used to expand an iterable object into the list of arguments.

2. List 4 things that the spread operator can do.

    - Concatenate arrays into a single array
    - Clone arrays or objects to have the same elements or properties as the original but do not share a reference
    - Inserting elements into an array, from one array to another at a specific index
    - Merging the properties of two or more objects into a single object.

3. Give an example of using the spread operator to combine two arrays.

    const array1 = [1, 2, 3];
    const array2 = [4, 5, 6];
    const combinedArray = [...array1, ...array2]; // [1, 2, 3, 4, 5, 6]

4. Give an example of using the spread operator to add a new item to an array.

    const array1 = [1, 2, 4, 5];
    const array2 = [3];
    const combinedArray = [...array1.slice(0, 2), ...array2, ...array1.slice(2)]; // [1, 2, 3, 4, 5]

5. Give an example of using the spread operator to combine two objects into one.

    const object1 = { a: 1, b: 2 };
    const object2 = { b: 3, c: 4 };
    const mergedObject = { ...object1, ...object2 }; // { a: 1, b: 3, c: 4 }

*Examples 3, 4, 5 used code snippets from Tabnine*

## Things I want to know more about

**Immutability and how it relates to updating the state in React apps**

*https://dmitripavlutin.com/javascript-object-assign/*

*https://immerjs.github.io/immer/*
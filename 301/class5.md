# Putting it All Together

## Thinking in React

1. What is the single responsibility principle and how does it apply to components?

    A component should (ideally) do one thing . If it ends up growing, it should be decomposed into smaller sub-components.

2. What does it mean to build a ‘static’ version of your application?

    It means to build a version of your application without interactivity at first. Static versions require a lot of typing and no thinking and adding interactivity requires a lot of thinking and not a lot of typing. Be careful not to use any state values during this process.

3. Once you have a static application, what do you need to add?

    UI interactivity via state.

4. What are the three questions you can ask to determine if something is state?

    - Does it remain unchanged over time? If true, it isn't state.
    - Is it passed in from a parent via props? If true, it isn't state.
    - Can you compute it based on existing state or props in your component? If true, definitely isn't state.

5. How can you identify where state needs to live?

    For each piece of state in your application:

    1. Identify every component that renders something based on that state.
    2. Find their closest common parent component—a component above them all in the hierarchy.
    3. Decide where the state should live:
        - Often, you can put the state directly into their common parent.
        - You can also put the state into some component above their common parent.
        - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.

        (Source: https://react.dev/learn/thinking-in-react)

## Higher Order Functions

1. What is a “higher-order function”?

    Functions that operate on other functions, either by taking them as arguments or returning them, are called higher-order functions.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

    Defines and returns an arrow function which takes the argument 'm' and checks if it is greater than 'n'. It's a comparator function to compare value n against m.

3. Explain how either map or reduce operates, with regards to higher-order functions.

    Map is a higher order function because it takes another function as an argument and applies that function to each element or an array. Reduce does the same but outputs or reduces the array to a single value given the function parameter.

## Things I want to know more about

**Where can I find sandbox projects for React apps that I can follow along with to increase my understanding?**
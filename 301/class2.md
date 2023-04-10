# State and Props

## React Lifecycle

1. Based off the diagram, what happens first, the 'render' or the componentDidMount?

    The render

2. What is the very first thing to happen in the lifecycle of React?

    Mounting. When an instance of a component is created and inserted into the DOM, it happens during the mounting phase. In this order: Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount.

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

    Constructor, render, ComponentDidMount, React Updates, componentWillUnmount

4. What does componentDidMount do?

    It loads anything using a network request or initialazing the DOM. Also to set up subscriptions. setState() can also be called here but will cause a rerender which could lead to performance issues.

## React State Vs Props

1. What types of things can you pass in the props?

    Props are things that you would pass to a function. They're what you want to intitialize your component, or how you would want your component to render. Maybe a display such as a title or subtitle. 

2. What is the big difference between props and state?

    State is something inside of a component. Props you pass into a component and state is handled inside of that component. Props is handled outside of that component. State must be updated inside and props outside of a component. When you change the state in an application, it's going to rerender that section in the application. With props, you have to change them outside of the component. **State is there for when you need to rerender and update the application based on what the user has done.

3. When do we re-render our application?

    When a change to state is triggered by user interaction. 

4. What are some examples of things that we could store in state?

    1. Form inputs like form fields, text fields, checkboxes, buttons
    2. Data fetched from APIs like external lists or data
    3. Counter data fetched from things like click events, timers, or other numeric values that change over time
    4. Notifications or feedback messages displayed to the user


## Things I want to know more about

**How to use bootstrap to create complex applications. What are some real world examples of this being implemented?**
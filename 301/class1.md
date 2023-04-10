# Introduction to React and Components

## Component Based Architecture

1. What is a Component?

    *"A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.*

    *A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.*

    *A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties."* (https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

2. What are the characteristics of a component?

    1. Reusability: Designed for reuse in different situations and applications. Some are designed for a specific use.
    2. Replaceable: Can be substituted freely with similar components.
    3. Not context specific: Designed to operate in different environment and contexts.
    4. Extensible: Extended from existing components to give new behavior.
    5. Encapsulated: Can depict interfaces without exposing details of internal processes, variables, or state.
    6. Independent: Designed to have minimal dependecies on other components.

3. What are the advantages of using component based architecture?

    *Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.*

    *Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.*

    *Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.*

    *Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.*

    *Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.*

    *Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.*

    *System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.*

    *Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.*
    (https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

## What is Props and how to use it in React

1. What is "props" short for?

    Properties

2. How are Props used in React?

    It is used for passing data from one component to another. It is passed in a uni-directional flow, one way from parent to child. It is used as read-only, data coming from the parent should not be changed by child components.

3. What is the flow of Props?

    Top-down unidirectional. Define properties in parent, pass properties to child, access and use properties in child, read-only for child.


## Things I want to know more about

*How can i use PropTypes to validate the types of props being passed to a component? How do I install and import PropTypes? Define? Use in arrays or objects? Benefits and limitations?*

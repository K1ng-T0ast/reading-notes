# Class 7 Notes

## Constructor Functions

- A function that constructs objects for us. Typing less, if we know what properties an object has, we can define those properties in a function.

- "duplicate properties" with different values

## Methods and Prototypes

- Object that is inherited by every object created by the constructor. Single place to define properties and behaviors that are shared by all objects.

- Pokemon.prototype.speak

# Reading Notes

## CSS Layout

### CSS Flexbox

1. Flexbox is designed for one-dimensional content. Explain what this means
   - It means that everything on a webpage is by default flat and similar to a rigid layout. Things like sidebars and articles sit next to each other so they can only be manipulated around another, not above or below or any other 3D direction.

2. Explain the difference between the main axis and cross axis.
   - Main axis could be dumbed down to left to right or along a row
   - Cross Axis runs in the other direction to the main axis, so it's the row that runs along the column.

3. How can using certain properties of flexbox negatively impact accessibility?
   - Moving the flow of items can change the way things are ordered in an HTML document, so a screen reader would typically make sense of a logical order and not a visual one.

### CSS Layout of Flexbox

1. What are some advantages of using flexbox over float?
   - Vertically centering a block of content inside its parent.
   - Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
   - Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

    Source: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox 

2. How does this topic connect with your long term goals?

   - Anything that provides a shortcut or a faster way of achieving your goals like a JS function or prototype is a welcome addition in the developer toolkit. Not sure what the long term goal would be but being able to adopt a clients vision in a shorter amount of time will ultimately make you more appealing as a job candidate.

## Things I Want to Know More About

**_How to utilize flexbox in a way that is visually appealing and subscribes to accessibility standards_**

**_How is this implemented in something we see in CSS Zengarden?_**
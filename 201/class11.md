# Class Notes (reading notes below)

## Responsive Layouts (CSS Topics)

- How to make our web apps look good on mant different devices
- Mobile first: design for the screen size that has the most accessiblity concerns. Small phones > work your way up
- CSS Breakpoint (media query)
   - Small phone: around 375x667
   - Large phone: around 1366x768
   - Desktop: around 1920x1080

## Debugging

**3 Pillars of Debugging**

1. Read your errors
2. Use console.log to audit your code not to trace your code. Leave really informative console.logs. Give yourself a message as to why and what is being logged.
3. Use the debugger statement to trace your code. Use every time to try to audit values, start leaving a debugger statement below.



**4 Types of Errors**

1. Syntax error: typos mostly, but also lacking closing brackets or semicolons etc.
2. Reference error: You are referencing or trying to reference something that does not exist. Return values are not as expected. 
3. Type error: The data type is not what is expected. Nulls that shouyld be objects. Using a method on a type that is incorrect.
4. Range error: Numerical issue. Like creating an array with negative space.

# Reading Notes

## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

  - We started out using proprietary plug ins like flash and silverlight which had security and accessibility issues. Now we use native HTML and JS APIs.

2. Describe the use of the src and controls attributes in the video element.

  - src is a path to the video you want to embed and controls allows the use of browser built in control interface or a custom API

3. Why is it important to have fallback content inside the video element?

  - In case the video doesn't load on older browsers as an example so you can provide a direct link to the video.

4. Write a very short story where <audio> and <video> are characters.

  - Once upon a time in the kingdom of technologica there lived two best friends who lived with each other, audio and video. They performed for the citizens and were great at it for audio was blind but could tell a great story and video was deaf but was full of expressiveness. One day the emperor decreed that every citizen must live alone to focus on what's important. The people grew angry because they relied on audio and video together but when separated it just wasn't the same. So the emperor made a special exception and allowed them to live together once again and the people rejoiced.

## Grid

1. How does Grid layout differ from Flex?

  - Flex has a one directional flow  and can optionally wrap and as such no way to declaratively control where an element ends up as they are being pushed along a single axis. Grid is mostly defined on the parent element whereas flexbox mostly happens on the children. Grid is better at overlapping, flexbox can push things away.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

  - A grid container is an element that has been set to grid using display: grid. Established grid context for child elements which are grid items. Items are placed onto the grid using grid lines which are divided up into rows and columns and numbered based on their position in the grid. You can specify placement of grid items on grid lines creating complex layouts.

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

  - A part of responsive design, improved performance to only download the size needed for the screen, better accessibility, search engine optimization benefits, and cross device compatability. 

2. Define the following img attributes srcset and sizes. Write an example of how they are used.

  - scrset defines the set of images the browser will choose between and what size each of them is, sizes defines media conditions like screen widths and tells browser what image is best to choose. Could be used if you had a large image of a menu item and wanted to make it viewable on both desktop and mobile.

3. How is srcset more helpful for responsive images than CSS or JavaScript?

  - Because of the order in which a page loads. It starts to download or preload any images before starting to load and interpret the CSS and JS.

## Things I want to learn more about

**_Custome JS APIs for in music or video controls and how to create dynamic elements in CSS for those_**
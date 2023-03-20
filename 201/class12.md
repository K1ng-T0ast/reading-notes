# Class Notes

## Grid Layout

- display: grid;
- grid-template-columns: 50px 50px 50px; as an example would give three columns at 50px each
- grid-template-rows: same thing but for rows
- New method: fr (fraction?) 1fr 2fr 1fr

# Reading Notes

## JavaScript Canvas

1. What does the canvas tag allow a developer to achieve?

  - Allows the drawing of 2D graphics using JavaScript.

2. What is the importance of the closing canvas tag?

  - Same as the audio and video tags, it allows for the use of fallback content that will display only if the browser doesn't support the element.

3. Explain what the getContext() method does.

  - Returns a render context object. Takes an argument which is the type of context ex 2D.

## Chart.js Documentation

1. What is Chart.js and how it can be brought into your project?

  - "Chart.js is a popular open-source JavaScript library for creating interactive and customizable charts and graphs on web pages. It allows developers to easily create different types of charts, including line charts, bar charts, pie charts, scatter charts, and more.

Chart.js is built on top of the HTML5 canvas element, which provides a powerful way to draw graphics on a web page. It has a simple and intuitive API that allows developers to customize the appearance and behavior of their charts, including the colors, fonts, labels, and tooltips.

Chart.js is widely used in web development for data visualization, business intelligence, and analytics applications. It is easy to use and requires minimal setup, making it a popular choice for developers who want to create professional-looking charts without spending a lot of time or effort. Additionally, it has a large community of contributors and users, which means there are many resources and examples available for developers to learn from and use in their projects."

*Source: openai.com when asked "What is chart.js?"*

  - It can be used in tandem with the HTML5 canvas element to bring graphics that do not rely on CSS into your project page and with relative ease rather tha writing many lines of DOM code.

2. List 3 different Chart types you can create using Chart.js.

  - Bar chart: a way of showing data values represented as vertical bars, like trend data and comparison of multiple data sets side by side.
  - Donut and pie charts: Most commonly used chart. Segment divided, arc of each segment shows proportional value of each piece of data.
  - Radar chart: showing multiple data points and the variation between them (think pokemon pokedex chart for stats)

## Easily Create Stunning Animated Charts with Chart.Js

1. What are some advantages to displaying data via a chart over a table?

  - Better at displaying visual data, easier to look at and distill information quickly.

2. How could Chart.js aid your previously created applications visually?

  - Cookie store, would have been able to use a line chart with different colors to represent different data sets or each of the 5 stores to show the trend of cookie sales over the hours of the day to showcase the disparity between the 5 without looking directly at a staggering amount of information.

## Things I want to know more about

**_How to utilize the plugins to make a data representation of selections in proceduarly generated surveys_**
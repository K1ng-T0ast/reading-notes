# Introduction to HTML and the Web

**_Learning about HTML helps to understand the foundation for all web development and is critical should full stack development be a field for study_**

## How Does the Web Work?

1. Compose a short poem describing how HTTP sends data between computers

> My computer is going to its favorite data candy shop
> It asks the candy store owner for its data to drop
> The candy store owner agrees with a loud data pop
> The data is spilled all over my computer and now it needs a mop

*side note I am terrible at poetry, note not to try as a career*

2. Describe how HTML, CSS, and JS files are parsed in the browser
   - Parses the HTML file first, then sends a request back to the server for the CSS and JS files or inline code from elements and then parses those. It then generates memory trees from the information parsed, executes, and paints a representation on screen for the user.

3. How can you find images to add to a website?
   - Google images, optional license filter, either save as to your computer or use the link address

4. How do you create a string vs a number in JavaScript?
   - To create a string you encapsulate the value in single or double quotes and a number you leave them out

5. What is a variable and why are they important in JavaScript?
   - Variables are containers that store values, it is a named reference for a value so that an unpredictable value can be accessed through a name when building out your code.


## Getting Started with HTML

1. What is an HTML attribute?
   - Attributes contain extra information about the element. It will not appear in the document. All HTML elements can have attributes, they are always specified in the start tag and usually come in name/value pairs like: name="value"
   - Some examples of attributes include the href or URL, src used to embed an image, width or height of an image, alt which shows the alternate text for an image, style for color font size and more, lang for language of a webpage,
   title which defines some extra info about an element.

2. Describe the anatomy of an HTML element
   - Opening tag which contains the name of the element wrapped in opening and closing angle brackets
   - Content which is the content of the element
   - Closing tag which is the same as opening tag except with a foward slash before the element name

3. What is the difference between article and section element tags?
   - An article represents a self-contained composition in a document, page, application, site, which is intended to be independetly distributable or reusable. Forum posts, magazine, blogs, comments, any independent line item of content.
   - The section element represents a generic standalone section of document which doesn't have a more specific semantic element to represent it. Sections should always have a heading with very few exceptions.

4. What elements does a typical website include?
   - A header, a navigation bar, main content, a sidebar, a footer.

5. How does metadata influence search image optimization?
   - It has the potential to make your page appear higher in relevent rearches performed in search engines. Specifying an author and description adds to this.

6. How is the meta tag used when specifying metadata?
   - It is data that is used to describe data. Some common uses include specifying character encoding, name and content attributes, language, favicons, proprietary metadata etc.

## Misc

### How To Design a Website

1. What is the first step to designing a website?
   - Define what you want to accomplish with it and make a plan. Ideation.

2. What is the most important question to answer when designing a website?
   - Decide what you want to accomplish, how the site will help you reach goals, and what needs to be done and in what order to reach those goals. What's my vision?

### Semantics

1. Why should you use an h1 element over a span element to display a top level heading?
   - Because it is a semantic element that gives the text it wraps around the role or meaning of a top level heading vs span that would make any element look like a top level heading but has no semantic value and therefore does not get extra benefits. Semantic elements slearly describes its meaning to both the browser and developer, so its a case by case scenario but best to use the right element for the right job.

2. What are the benefits of using semantic tags in our HTML?
   - Search engines consider the contents like keywords to influence rankings, screen readers see it as a signpost, finding blocks of meaninful code is easier, suggest to developer the type of data that will be populated, mirrors proper custom element compponent naming

### What is JavaScript?

1. Describe 2 things that require JavaScript in the browser?
   - Animating graphics on a page, scrolling through lists, interacting with content

2. How can you add JavaScript to an HTML document?
   - The script element or you can store it in an external file such as script.js and replace the script element in the HTML doc using the file as the src inside the tag. You can also do it inline but this is not good practice.


## Things I want to know more about

**Favicons or custom metadata**
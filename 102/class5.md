# CSS

+ Stands for cascading style sheets
   - It's how we style our HTML of the websites we're working on, it is a language for specifying how documents are presented to users, how they are styled, laid out, etc.
   - HTML is the most common markup language, others include SVG or XML
   - It is a rule based language - define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page

+ CSS Syntax
  - Choose a selector, followed by a set of curly braces
  - Inside the braces will be one or more decvlarations, which take the form of property and value pairs, such as color or font-size followed by a colon
  - CSS reference on google for complete property pages
  - Check CSS implementation status for new features being added to which browsers

# How to Add CSS

+ Three ways of inserting a style sheet
  - External
  - Internal
  - Inline

**External**

+ With an external style sheet, you cna change the look of an entire website by changing just one file
+ Each HTML page must include a reference to the external style sheet file inside the link element, inside the head section

> link rel="stylesheet" href="my style sheet.css"

**Internal**

+ Internal styles are defined within the style element, inside the head section of an html page

**Inline**

+ Inline styles are defined within the style attribute of the relevant element

> h1 style="color:blue;text-align:center;">This is a heading<

Multiple style sheets can be had, with order precadence. If before, then true.

**Cascading Order**

+ All styles will cascade into a new virtual style sheet by following rules, in order of priority
  - inline style inside an HTML element
  - external and internal style sheets in the head section
  - browser default

## CSS Comments

Comments are used to explain the code and may help when you edit the source code at a later date

Defined by: /* this is a single line comment */ 

## CSS Colors

+ Color name
+ CSS text color
+ border color
+ color values, RGB (255, 99, 71), HEX values (#FFFFFF), hsl values
  - shades of gray are defined using equal values for all three light sources in RGB
  - alpha color at the end of RGB chain specifies opacity (0.5)
+ 3 digit hex code can only be used when both values are same for each component such as ff00cc
+ HSL is hue, saturation, and lightness written as first number without percent signs and the other two with

## Backgrounds

background-color
background-image - 	Sets the background image for an element
background-repeat - Sets how a background image will be repeated (repeat-x, no-repeat)
background-attachment - Sets whether a background image is fixed or scrolls with the rest of the page (scroll, fixed)
background-position - Sets the starting position of a background image

can specifiy opacity by using

opacity: 0.3;

Opacity can be applied using RGBA

background-image: url("paper.gif");

**SHorthand**

One declaration. Instead of this:

background-color: #ffffff;
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;

This

background: #ffffff url("img_tree.png") no-repeat right top;
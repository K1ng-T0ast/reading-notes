# HTML

## *Wireframe & Design

### *What is a wireframe?

- A wireframe is an aristic blueprint for a website, app, or product. This allows the designer and client to plan on how they want users to process and interact with the information on a product. 
- Typically done in plain black and white diagrams before anything is built in code, it's a good way to know how a user will interact with the interface.
  - This includes but is not limited to positioning of buttons, menus, headers, footers, text boxes, pictures.

### *How To Wireframe

- Wireframes drawn with paper and a pencil, or at a whiteboard, have the advantage of looking and being very easy to change, which can help tremendously in early conversations about your website or product.

- With the help of paper-prototypes, you can test with end users at every stage of ideation and design. Changes at these stages are much easier—and therefore cheaper—than changes deemed necessary after coding is under way.

- Switching later to software (after initially hand-drawing your wireframe) allows you to keep track of more detailed decisions.

Some ways to structure the process from design to implementation:

- wireframe > interactive prototype > visual > design
- sketch > code
- sketch > wireframe > hi-def wireframe > visual > code
- sketch > wireframe > visual > code

Tools for Wireframing

[UXPin](https://www.uxpin.com/)

[InVision](http://www.invisionapp.com/)

[Wireframe.cc](https://wireframe.cc/)

[Balsalmiq](https://balsamiq.com/)

***6 Steps to make a wireframe***

1. Do your research
2. Prepare your research for quick reference
3. Make sure you have your user flow mapped out
4. Draft, don't draw. Sketch, don't illustrate.
5. Add some detail and get testing
6. Start turning your wireframes into prototypes

***Make your wireframe good with clarity, confidence, and simplicity***

## HTML and its Pieces

***Hypertext Markup Language***

**Web Application vs Website**

*Website is a client to a server (html + css + js) [frontend languages]*

 - Client is frontend (hypertext markup language + cascading style sheets + javascript) sends request to server, server delivers code and client displays information)

*Web Application*

 - Similar to website except a database layer is added. After request is made by client to server, then server sends to database for verification and more information, back to the server and then to the client

*Backend Languages (some)* 

Server = Python, Java, Javascript, C#

Database = MongoDB, SQL

**HTML = content & structure**

**CSS = presentation**

**Javascript = action**

*HTML*
	
 - Tells the browser what the content is. Text, headlines, images, links. Communicates how content should be organized

*CSS*

  - Tells the browser how the content should look. Text color, font style and size, placement of content, size and type, 

*Javascript*
	
 - A programming language that allows dynamic interactions with the browser. Tells the browser what is should do when certain things happen. User clicks a button, a form is submitted, page load, scroll page, fetch additional data

## HTML

HTML is a *markup language* that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on.

**Anatomy of an HTML Element**

1. The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.

2. The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

3. The content: This is the content of the element, which in this case, is just text.

4. The element: The opening tag, the closing tag, and the content together comprise the element.

Attributes contain extra information about the element that does not appear in the actual content. 

> I.E. - class is an attribute name and "editor note" is the value.

Attributes that set a value always have:

1. A space between it and the element name (or the previous attribute, if the element already has one or more attributes).

2. The attribute name followed by an equal sign.

3. The attribute value wrapped by opening and closing quotation marks.

**Nesting Elements**

Can be put inside other elements to add other effects, example below.

> <p>My cat is <strong>very</strong> grumpy.</p>

Notice how we have to close both elements in order for the effect to take place.

Void elements have no closing tag and no inner content because something like an image element doesn't wrap content to affect it. Its purpose is to embed an image. 

***Anatomy of an HTML Document***

1. !DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However, these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.

2. html></html> — the html> element. This element wraps all the content on the entire page and is sometimes known as the root element. It also includes the lang attribute, setting the primary language of the document.

3. head></head> — the head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.

4. meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this, and it can help avoid some problems later on.

5. meta name="viewport" content="width=device-width" — This viewport element ensures the page renders at the width of viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.

6. title></title> — the title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.

7. body></body> — the body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

*Some Atttribute defenitions*

> alt

  -Alternative attribute, which specifies descriptive text for users to see if the image cannot be seen.

> src

  -Source attribute, contains the path to (image) file.

**Marking Up Text**

 - Headings, h1 > h6 element
 - Paragraphs, p element
 - Lists
   - Unordered lists are wrapped in a ul element
   - Ordered lists are wrapped in a ol element
   - Each item inside the lists is put inside a li element
- Links, a element

Anything in HTML in between < !-- and --> is an HTML comment. The browser ignores comments as it renders code but its a way to write helpful notes about code or logic.

## Semantics

In programming, **Semantics** refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?", or "what purpose or role does that HTML element have" (rather than "what does it look like?".)

***Javascript***

In JavaScript, consider a function that takes a string parameter, and returns an li> element with that string as its textContent. Would you need to look at the code to understand what the function did if it was called build('Peach'), or createLiWithContent('Peach')?

***CSS***

In CSS, consider styling a list with li elements representing different types of fruits. Would you know what part of the DOM is being selected with div > ul > li, or .fruits__item?

***HTML***

In HTML, for example, the h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

On the other hand, you could make any element look like a top level heading. Consider the following:

> span style="font-size: 32px; margin: 21px 0;">Not a top-level heading!</span>

This will render it to look like a top level heading, but it has no semantic value, so it will not get any extra benefits as described above. It is therefore a good idea to use the right HTML element for the right job.

HTML should be coded to represent the data that will be populated and not based on its default presentation styling. Presentation (how it should look), is the sole responsibility of CSS.

# Class 4 Notes

## CSS Positioning

**Positions**

1. Static - Default for almost all elements, browser positions them and they cannot be moved

2. Relative - elements can be positioned relative to their parent and siblings. Can be moved using top left bottom right.

3. Absolute - Slightly removed from the normal flow. Can be positioned over sliblings or outside of the parent

4. Fixed - Fully removed from parent and sibling layout. Positioned according to browser window.

5. Sticky - Combo of relative and fixed

## JS Functions

**A Variable for block of code**

- Function declaration - defines a block(s) of code to be reused
- Function execution - run all the code in the function declaration. Function call.

**Function parameters: variable that you define for the function, in the function declaration, only for that function. wihin the parentheses. A placeholder.**

**Function arguments: values for parameters. Could be an expression that evaluates to a value.**

**Return statement: pass a value from the functions scope to wherever the function is being called. Must return something for the function to be accessed somewhere**

**Scope: global vs function. Values that are accessible at different parts of our program.**

    function askQuestion(question, answer){
    let response = prompt(question).toLowerCase();
        if (parseInt(response)){
        response = parseInt(repsonse);
    }
        if (response === anwswer){
        return true
        } else {
        false;
        }
    }

    let isCorrect = askQuestion('What is my favorite pokemon', 'pikachu');
    console.log(isCorrect);

    let questions = ['Who is fav pokemon', 'what is my age'];
    et answers = ['pikachu, 33];

    for (let i = 0; i < questions.length; i++){
        let isCorrect = askQuestion(questions[i], answers[i]);
    if (isCorrect){
        alert('Great!);
    } else {
        alert('Wrong!);
    }
    }

# Reading Notes Class 5

**Using images and adding color brings dimension, context, and fun to our otherwise boring websites which we'll want to utilize in order to make our about me pages come to life in a more meaningul and engaging way. Changing fonts is a great way to capture attention if there's a lot of text on your page and adding other styling to fonts could make some text appear more important and puts an ease on the eyes**

## Images, Color, Text

### Using Images in HTML, Common Image Types and Image Formats

1. What is a real world use case for the alt attribute being used in a website?
   - When the user is visually impaired and is using a screen reader to read the web out to them.
   - Searching for an image using an engine and finding that tag related to an image in an alt text

2. How can you improve accessibility of images in an HTML document?
   - Use CSS background images instead of HTML
   - Provide an alt text and avoid redundant alt tags
   - Utilize accessible link text in links

3. Provide an example of when the figure element would be useful in an html doc?
   - When there are a ton of images and captions for each image on a page and a screen reader is trying to determine which caption goes with which image
   - Providing a grouping of a musical artists discography with album titles under each album picture

4. Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community
   - A .gif image is like a short video that plays on a loop, like the ones you see on social media. Maybe a funny or cute animal animation plays over and over.
   - An .svg is like a drawing or picture of your grandchildren that you can make to any size without getting blurry or hard to see. You could see an example of this in something like a billboard.

5. What image type would you use to display a screenshot on your website and why?
   - Something that is lossless like PNG or lossless WebP so if there's any text in the screenshot it doesn't get lost under compression.

### Color in CSS, Styling HTML Elements

1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
   - Foreground color could be the color of the text you read, or stuff that you may actually want to read. Background color could be the color behind the text or color that fills up the space behind all the text or something like a button.

2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
   - I might add some background color to something that is dark and change the color to something that is higher contrast and works with the color of the background as complementary, like neon green over black or yellow over purple. I would also change the links to a different complimentary color so that the main text is easily identifiable over the the links or other elements.

3. What should you consider when choosing fonts for an HTML document?
   - Choosing a font that is web safe or ones that work across all systems

4. What do font-size, font-weight, and font-style do to HTML text elements?
   - Font size: changes the size of the text in an HTML document 
   - Font weight: Sets how bold the text is using many variants
   - Font style: Used to turn italic text on or off

5. Describe two ways you could add spacing around the characters displayed in an h1 element.
   - letter spacing to add spacing between individual letters
   - word spacing to add spacing between the words 

## Things I want to know more about

**_How to dynamically place in image in CSS so that it remains static on the screen in full resolution and does not repeat itself, instead the text and boxes move like they're floating on top of the image_**
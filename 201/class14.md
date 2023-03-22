# Reading Notes

## CSS Transforms

1. What does a CSS transform allow the developer to do to an element?

    - It allows the general layout techniques to be used in alternative ways to size, position, and change elements using 2D or 3D transforms. 2D works on the x and y axis and 3D works on the x, y and z axis, helping to create a sense of depth. 

2. Provide an example of a transform and how you could see that being used on a website.

3D Cube Demo
HTML

    <div class="cube-container">
    <div class="cube">
        <figure class="side front">1</figure>
        <figure class="side back">2</figure>
        <figure class="side left">3</figure>
        <figure class="side right">4</figure>
        <figure class="side top">5</figure>
        <figure class="side bottom">6</figure>
    </div>
    </div>

                
CSS

    .cube-container {
    height: 200px;
    perspective: 300;
    position: relative;
    width: 200px;
    }
    .cube {  
    height: 100%;
    position: absolute;
    transform: translateZ(-100px);
    transform-style: preserve-3d;
    width: 100%;
    }
    .side {
    background: rgba(45, 179, 74, .3);
    border: 2px solid #2db34a;
    height: 196px;
    position: absolute;
    width: 196px;
    }
    .front {
    transform: translateZ(100px);
    }
    .back {
    transform: rotateX(180deg) translateZ(100px);
    }
    .left {
    transform: rotateY(-90deg) translateZ(100px);
    }
    .right {
    transform: rotateY(90deg) translateZ(100px);
    }
    .top {
    transform: rotateX(90deg) translateZ(100px);
    }
    .bottom {
    transform: rotateX(-90deg) translateZ(100px);
    }

This could be used in an online game where a character has to hit a box to open it and the transform movement shows the user that this is an interactive item.

## CSS Transitions and Animations

1. What does a CSS transition allow the developer to do to an element?

    - You can alter the appearance and behavior of an element whenever a state change occurs like hovering, focusing, active, targeted.

2. How does a CSS animation differ from a CSS transition?

    - Animations can set multiple points of transtion upon different keyframes while transtions only provide a change from one state to another. 

3. What are some benefits to using CSS transitions on websites?

    - CSS transitions are all hardware accelerated and can reduce server load and are also optimized so they can perform without causing issues on the viewing device, it can improve user experience to make websites more visually appealing, and are browser compatible with most modern browsers.

4. How this topic fit in with your long-term goals?

    - Part of my long term goal is to be proficient in many programming languages, even if JavaScript and full stack development is not my end game. This will help to keep me updated and informed in the conversation of programming as it evolves. It will also help to move me through code 301 as I'm sure the projects will rely on utilizing many of these concepts.

## Things I want to know more about

**_What is the most effective design plan for utilizing CSS transitions and animations in different applications such as web or app? Is there a certain limit to how many we wish to use? What is the industry standard for using these to accomplish our goal and maintain a clean and consistent structure in the modern web?_**
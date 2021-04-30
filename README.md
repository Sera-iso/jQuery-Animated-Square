# jQuery-Animated-Square
jQuery animation using the animate() method 🟥

## Syntax
$(selector).animate({params}, speed, callback);

Breakdown of the sample animation:

- I targeted a <div> as the selector I wanted to animate.
- I applied the .animate() method to the <div> and defined the CSS properties to animate: height and width of the square.  Note: most of the CSS properties can be manipulated by writing them camel-cased e.g. paddingTop instead of padding-top.
- I added the optional speed parameter to control how slow the animation executed.
- It is possible to add a callback function to execute something after the animation completes.
  
Queues:
I wrote multiple .animate() methods that created a queue running different properties sequentially.

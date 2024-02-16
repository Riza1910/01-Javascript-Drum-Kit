## Javascript Drum Kit ##

This is the first project of Javascript30 challenge. 

This JavaScript code sets up a drum kit where pressing certain keys triggers corresponding sounds. It also provides visual feedback by adding a CSS class to visually indicate which key is being played and removing it when the key is no longer pressed. The code leverages event listeners, DOM manipulation, and CSS transitions to achieve this interactive drum.


## Concepts utilized in making this project -

1) Event Listeners:
In JavaScript, event listeners are a fundamental concept used to handle interactions with a webpage.
They allow you to specify a function to be executed when a certain event occurs on a DOM element.
In this code, window.addEventListener('keydown', playSound) attaches an event listener to the window object, specifically listening for the 'keydown' event.
When a key is pressed, the playSound function is invoked.

2) Functions:

Functions in JavaScript are blocks of reusable code that perform a specific task.
They encapsulate a set of statements and can accept input parameters and return values.
In this code, playSound(e) and removeTransition(e) are both functions defined to handle specific tasks related to playing sounds and removing transition effects, respectively.

3) DOM Manipulation:

Document Object Model (DOM) manipulation involves accessing and modifying elements on a webpage using JavaScript.
It allows dynamic changes to be made to the content, structure, and style of a webpage.
In this code, DOM manipulation is used to select specific elements using document.querySelector() and to modify their attributes and classes.

4) Event Object:

In JavaScript, when an event occurs, an event object is created and passed as an argument to the event handler function.
It contains information about the event, such as the type of event (e.type), the target element (e.target), and additional properties depending on the event type.
In this code, the event object e is passed to the playSound function and used to determine which key was pressed (e.keyCode).




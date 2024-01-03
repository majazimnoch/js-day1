# Scroll effect with JS "Light"

## Intro
This is the first project of my 30-day coding with JavaScript challenge. The project includes following tech stuff: html, css and JavaScript. 

## Idea
The goal was to make an effect where text is being shown only when the user moves the mouse so the cursor points on the position of the text on the screen. 

## Breaking down the code
The JS code is capturing the mouse movement on the entire HTML document and updating properties (--x and --y) on the document's root documents based on the mouse coordinates. 

I started off by creating a var pos.

pos.addEventListener('mousemove', e => { ... });: This line adds an event listener to the root element for the 'mousemove' event. The callback function inside the listener is executed whenever the mouse is moved over the document.

## Demo

Click <a href="https://thriving-kangaroo-eddb6d.netlify.app/" target="_blank"> Here </a>.
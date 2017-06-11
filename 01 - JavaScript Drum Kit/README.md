Notes for lesson 1 - JavaScript Drum Kit

HTML data-* attributes: Introduced in HTML5, data-* attributes (where * can be anything you want)allow us to store custom data on any HTML element. Each div.key (<div class="key" data-key="...">) and audio element in the provided HTML file has a data-key attribute which corresponds with a keyboard button.

HTML Keyboard Input Element <kbd> represents user input and produces an inline element displayed in the browser's default monospace font.

CSS playing class & pre-defined style: The provided CSS file already has a playing class defined with some rules in it. We will apply this class to the correct element, depending on the key pressed by the user, and remove it once animation is finished.

We bind an event to our keys when they are pressed, as follows:
window.addEventListener(‘keydown’, function(e){}) //note keydown is in quotes. And it is window, not document.
document stands for DOM
and window is the global object in a browser, or the root object of the DOM

Use forEach to iterate through a NodeList, as was done with keys here
Prefer named functions for use as event callbacks
For data attributes, keep it simple! I don’t always need to get the element and search its dataset to take advantage of the selectors.
Notes for lesson 2 - JS and CSS Clock   

CSS:

transform: rotate(...deg) - The transform property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements. (https://www.w3schools.com/cssref/css3_pr_transform.asp) 

transform origin - The transform-origin property allows you to change the position of transformed elements. 2D transformations can change the x- and y-axis of an element. 3D transformations can also change the z-axis of an element. (https://www.w3schools.com/cssref/css_animatable.asp)

transitiom: all 0.5s - CSS3 transitions allows you to change property values smoothly (from one value to another), over a given duration. (https://www.w3schools.com/css/css3_transitions.asp)

transition-timing-function - The transition-timing-function property specifies the speed curve of the transition effect. This property allows a transition effect to change speed over its duration. (https://www.w3schools.com/cssref/css3_pr_transition-timing-function.asp)

JS:

Date - The Date object is used to work with dates and times. Date objects are created with new Date(). https://www.w3schools.com/jsref/jsref_obj_date.asp

setInterval - The setInterval() method calls a function or evaluates an expression at specified intervals (in milliseconds). The setInterval() method will continue calling the function until clearInterval() is called, or the window is closed. The ID value returned by setInterval() is used as the parameter for the clearInterval() method. Syntax => setInterval(function, milliseconds, param1, param2, ...) 
https://www.w3schools.com/jsref/met_win_setinterval.asp

function setDate() {
    const now = new Date();
    const seconds = now.getSeconds();
    const minutes = now.getMinutes();
    const hours = now.getHours()

Style object
The Style object represents an individual style statement.

Access a Style Object
The Style object can be accessed from the head section of the document, or from specific HTML element(s).
https://www.w3schools.com/jsref/dom_obj_style.asp


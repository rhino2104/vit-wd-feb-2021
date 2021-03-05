2 ways to utilize JS with HTML and CSS

answer: script (can be used anywhere in the html document)

External JS File.  Best practice is script.js like an external CSS sheet.  Use script tag <!--<script src=""> --> to link instead of "link" tag. You can use multiple external scripts to point to different script sheets.

// Functions

syntax

function nameOfYourFunc(){

}

utilization of you the function
    
    1. declaration
    2. invocation

The Event Elements
-(Most Common)
    form
    button (default "click" event lister)
    input

Event Features
    Listeners
    Handlers

The event listeners are tied to the HTML element.

example 
    <!-- <button onclick="turnBGblue"> change me to blue -->
The button is tied to a JS.script file with the JS that changes the background to blue.  The button defaults to listen for the push.  The "onclick" is the Handler.


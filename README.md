<h1>Simple Calculator App</h1>

This is a simple calculator app built with React.js. It includes basic mathematical operations such as addition, subtraction, multiplication, and division.

<h1>Features</h1>

Input field to type in a number

Four buttons for mathematical operations

Display of the current result

Two reset buttons to clear the input field and the result

<h1>How to use</h1>

Type in a number in the input field

Press one of the four mathematical operation buttons to perform the 
operation on the input number and the current result

Press the "Reset Input" button to clear the input field

Press the "Reset Result" button to set the result back to zero

<h1>Additional Notes</h1>

The input field only accepts numbers

The result is displayed using a ref to a p element

The input field and the mathematical operation buttons are in a form element

Basic CSS styles have been added to make the app look presentable

<h1>Usage</h1>
useState is used to keep track of the current result

useRef is used to access the input field and the result display element

The mathematical operations are implemented as functions that are passed as callbacks to the corresponding buttons. 

The event preventDefault() is called to avoid page reload.

The reset functions are also implemented as functions that are passed as callbacks to the corresponding buttons.

<h1>Acknowledgements</h1>

This project makes use of React.js, a popular JavaScript library for building user interfaces.

The app uses CSS and HTML for styling and layout respectively.

<h1>Note</h1>

This is a simple calculator app, it is not intended to be a fully functional scientific calculator.
The knowledge cutoff is 2021-09, so some of the recent updates of React.js is not covered here.

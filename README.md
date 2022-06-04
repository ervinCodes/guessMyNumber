# guessMyNumber
Guess My Number! Game using HTML, CSS and Javascript

This small project taught me the fundamentals of event handling.  These events are signals fired inside the browser window that notify changes in the browser environment and allows web pages to respond appropriately.

Event handler code can be made to run when an event is triggered by assigning it to the target element's corresponding onevent property, or by registering the handler as a listener for the element using the addEventListener() method. 

A few key notes that really helped was understanding what value you wanted to change. 

For example, to change text only you would use something like: 

document.querySelector('.number').textContent = '13';

While to get the value property in an input you could write something like: 

document.querySelector('.guess').value;

I learned to handle the click of a button in which each click adds to the guessing number:

document.querySelector('.check').addEventListener('click', function () {
  console.log(document.querySelector('.guess').value);
});

Still much to learn, but a lot was learned.

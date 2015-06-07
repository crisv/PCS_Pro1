# PCS_Pro1
Foundations Pro Class - Assignment 1

Objectives

    Create a simple, interactive web site using event listeners and DOM manipulation
    Use a JavaScript loop
    Use attribute selectors in jQuery calls
    Review basic git and github use
    Publish the site using github pages

Things to do
Part 0 - set up the assignment

Steps

    Make a repository and establish a remote on github.com. This should be review
    Create a gh-pages branch both locally and on github.com to set up web hosting
    Work on the master branch unless you are deploying via the gh-pages branch
    Copy the contents of this gist to a file named index.html in your repo
    Add, commit, and push your file to github.com

This template contains lots of comments, some pre-existing code, and places for you to answer questions and create new code.
Part 1 - take the quiz

Steps

    Read all the code and the comments. Take your time.
    Answer the quiz questions by updating the file.
    Test, add, commit, and push your code on master
    Merge your code to gh-pages and push to deploy your site.

Part 2 - update event listener

Make the last few changes to create the “Run Script” event listener

Steps

    Replace the alert() function with the given loop_and_display() function in the “Run Script” button event listener
    Test, add, commit, and push your code on master
    Merge your code to gh-pages and push to deploy your site.

Part 3 - create event listener

Create a new event listener for the “Clear” button,

Steps

    Use an attribute selector like the first event listener, but select the “Clear” button
    Remove the “selected” class when the click event happens
    Replace the html in the #output_area div with a paragraph containing the text, “Click the Run Script button.”
    Test, add, commit, and push your code on master
    Merge your code to gh-pages and push to deploy your site.

Here’s some code for an event listener that does something similar. You’ll have to adapt it by replacing stuff. You can’t use it the way it is.

$('input[type="button" ]').click( function(){
  console.log('Caught a button click event.');
  $("#some_div").removeClass( 'some_class' );
  $("#some_div").html( "<p>Some text.</p>");
});

Part 4 - convert while loop to for loop

This part is “extra credit”. Only do this if you have time.

The while loop is a good place to start learning loops because it’s easy to see what’s happening.

var count = 0;
while (count<10) {
  // do something;
  count++;
}

These kind of counting loops are so common, there’s a more compact way to do them. It’s called the “for loop.”

Steps

    Research the for loop at w3schools and MDN
    Convert the while() loop to a for() loop in the loop_and_display() function.
    Test, add, commit, and push your code on master
    Merge your code to gh-pages and push to deploy your site.


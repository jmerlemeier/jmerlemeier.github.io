## June 24, 2019

## HTML&CSS by *Jon Duckett*

### Ch. 1, The ABCs of Programming
- Writing a script
  * State your goal
  * List the tasks needed to achieve goal in a *script*
  * Code each step using Javascript
- Computer languages have vocabulary and syntax. Vocabulary is the words used and syntax is how they are put together.
- Computers do not make assumptions nor do they have memory, they solve problems programmatically. Here is a great example from the reading:
  * Find height of 1st person
  * Store as "tallest person"
  * Look at the height of the remaining people, one-by-one, and compare their height to the "tallest person".
  * At each step, if you find someone whose height is greater than the height of the "tallest person", he/she/they becomes the "tallest person"
  * Once you have checked all the people, tell me which one is tallest. 
- You can sketch talks using a flowchart

---------------------------------------------------------------------

### Ch.2, Basic Javascript instructions
- Expressions
- Operators
  * arithmatic 
  * string: + . Joining 2+ strings is called **concatenation**

---------------------------------------------------------------------

### Ch.3, Funtions, Methods, and Objects
- Used to organize code
  * Function: series of statements grouped together because they form a specific task
  * Method: Same as function *but* are created inside and are part of object
  * Objects: Made of properties and methods
  * Built-in objects: Come with the browser

- Basic Function
  * Functions store the code required to perform a specific task.
  * Has a name(identifier), parameters, statements in a code block that are called, and return value.
  * Declaring a function: name it and give statements
  * Calling a function: functionname();
  * Parameters: a function with specific information. ex: function getArea(width, height) These words act like variables.
  * Arguments as values the function should use to perform task. ex: getArea(3, 5)

---------------------------------------------------------------------

### Notes from Stephanie's lecture on functions
- Functions do work.
- Functions have three parts:
  * inputs (aka "parameters") - turkey, pepperjack, wheat
  * work - making a sandwich
  * output - sandwich
- ...and then we need to be able to run them, give them their inputs, and receive their outputs. 

- Functions give us *abstraction* - the ability to get stuff done without worrying about how it's happening "under the hood". We can write our logic once and use over and over again with a variety of inputs to get customized results. 

#### Syntax

Using above sandwich example...we need:
- a name
- a place to hold inputs
- a place to define the work
- a place to say what the output should be

function makeSandwich(meat, cheese, bread) {

}

---------------------------------------------------------------------

[Return to Homepage](README.md)
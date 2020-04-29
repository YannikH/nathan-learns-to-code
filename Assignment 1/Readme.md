# Assignment 1 - Let's write some functions!
**1A: Hello World!**

It's simple, let's start by writing "Hello World!" to the console!

We hope you're familiar with some basic datatypes, like strings, but in case you forgot, a string is a piece of text, it's surrounded by either single quotes `''` or double quotes `""`

The desired end result is that you can use the `console.log` function in javascript, to write "Hello World!" to the console.

**1B: Hello, specific person?**

Ok so now that we have that whole console log thing out of the way, let's get in to the idea of functions.

A function is a bit of code that you pre-write and can run multiple time with different information passed in to it. If you're familiar with excel, you might have used things like `=ADD(cell, cell)`, this is a function! In the case of the excell `ADD` function, you give it two cells to add the values together of.

These two cells make up the *parameters* of the function. Most functions you'll write will have parameters, this is where the magic happens, you can make the same bit of code run with different parameters, to do different things!

You can find out more about parameters [here!](https://www.w3schools.com/js/js_function_parameters.asp)


For assignment 1B, we want you to write a function that takes a single parameter, which is the name of a person as a string, it will then print "Hello [name of person]!" to the console.
The function should be called `helloPerson`, and I should be able to call it using `helloPerson("Steven")`, and see "Hello Steven!" in the console.


This will involve writing a function, and adding to strings together. Fortunately, you can just combine strings with `+`, there's other better ways to do it that you'll learn in the future, but for now let's just keep it simple. Example of adding strings: `console.log('Hello ' + 'world!')`
Adding strings together in code is called string concatenation.

**1C: Rude responses?**

Now that you've taught a computer how to greet people, the next logical step is teach the computer to be prejudicial.

Copy your `helloPerson` function from 1B, and rewrite it to respond with "Fuck you [name]" when the person's name is more than 5 letters.

If you want to know how to find out how long a name is, you can find that information [here!](https://www.w3schools.com/jsref/jsref_length_string.asp)
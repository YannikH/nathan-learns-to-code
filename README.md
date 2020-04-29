
# nathan-learns-to-code

Welcome to nathan-learns-to-code
This is where allegedly nathan learns to code

We're not super sure if that will happen yet, but we remain optimistic

---
### overview
**language**
In this repository we'll be writing some coding exercises, they're gonna be real simple, and they're gonna be focused on **javascript**, you're also allowed to do them in other languages, but we don't suggest silly things like that, since you might just fall down the "what language to choose rabbit hole".

**submitting assignments**
For every assignment, you'll be working in a new branch, then all the work you'll do in either a folder or file in the /answers repository. Generally the assignments can fit in a single file, and if they don't, we'll make sure to mention it! These files don't need to contain code that works, or can run on its own, we just use it as a dump for stuff to review together.
When you feel done with an assignment, just create a pull request and we'll review it together.

**work guidance**
If you'd like help with an assignment, feel free to reach out to us any time, we can help in a variety of ways, ranging from a hint in the right direction or a link to some documentation, all the way to pair programming.

You can write your code in an editor and copy-paste it in to the console of your browser, you can write your code directly in to the attached template.html, or you can copypaste it in to the eval box in the template and read the results from the console. In either case, you will not be building any front-end, and output will be handled through the console.

*Ready? Well let's get to it!*

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

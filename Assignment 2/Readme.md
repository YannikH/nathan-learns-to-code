# Assignment 2 - Variables & Arrays
**2A. Let's do the math!**
Ok so let's use a freaking variable. A variable is basically just a little box for a value, it's like a label you file something under for you to get it from later. In javascript we generally use the keyword `let` the first time we tell the computer about a variable(this is called declaration).

An example of a variable in use would be:
```
let daysInTheYear = 365
let daysInAWeek = 7
let weeksInAYear = Math.round(daysInTheYear / daysInAWeek)
console.log('there are ' + weeksInAYear + ' weeks in a year!')
```

Write a piece of code that makes a variable called `myCountingVariable` and give it a value of 0, then make some other variables that have numbers as their value, and add them, multiply them, subtract and divide them however you feel fit. Honestly just do *anything* with variables and print it to the console, like adding two numbers stored in variables together and printing it.

**2B. Remembering who we greeted.**
In this assignment, we want you to re-take the code from assignment 1B. If you don't think your code for that assignment was very nice, you can just take this code.
```
function helloPerson(name) {
  console.log('Hello ' + name + '!')
}
```
What we want to do now is for the computer to tell you the last person who was greeted, assuming anybody was greeted before.
What we can do for this is define a global variable outside the function, what this means is that the variable exists outside the function independently from it, meaning it stays around after the function is run.
Example test code:
```
helloPerson('Steven') // this should print "Hello Steven!"
helloPerson('Jacob') // should print "Hello Jacob! Steven just got here!"
helloPerson('Nicholas') // should print "Hello Nicholas! Jacob just got here!"
```

**2C. We're not a goldfish, we can remember more than one name**
Holy shit we're diving in to arrays now, this one is gonna be a fair bit harder than what we had before.

If you want a variable to be a list of stuff, like a list of names, you'll most commonly use an array. Now in theory we could talk a lot about what an array is, how it works in different languages, and when to use it, but we won't do that because let's just write a goddamn array first.

The basic way of making an array in javascript is
```
let myArray = [] // an empty array
```
You can also right away put values in it like this:
```
let arrayWithNumbers = [1, 2, 3, 4]
let arrayWithNames = ['Jonas', 'Steven', Nicholas']
```
So you might have noticed by now, `[]` is how you tell javascript you want an array, and if you want to put things in an array you just throw them in as comma separated values.

If you want to retrieve a single value from an array, you can it based on its place in the array, called the index. The first item is 0, so getting the first name of our array from the previous example would be done with `arrayWithNames[0]`, so `console.log(arrayWithNames[0])` would print "Jonas"

Modify the code of assignment 1B to add a name to an array of names every time somebody is greeted. You don't have to worry about filtering duplicates or anything. Whenever someone is greeted print the whole array, you can do that by just using `console.log` and passing in the array instead of a string.

**2D. Ok maybe we're like half goldfish, let's only remember like 5**

Take your code from assignment 2C, and make a version where only the last 5 names get stored in the array, anything older is removed again.
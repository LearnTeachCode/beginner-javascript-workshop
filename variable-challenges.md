# Practice challenges: Variables and data types

Time to tinker with code and break stuff! Below are several practice challenges where you either need to solve a bug, *create* a bug, or write some code from scratch.

:trophy: For all of these challenges, the goal is ***have fun!*** It doesn't matter if you're correct or not. Like they say, we learn more from our failures than from our successes. So let's have fun "failing", breaking things on purpose, and learning from the experience!

**We'll be using the following tools to run and test our code today:**

  1. Use [**Python Tutor**](http://pythontutor.com/javascript.html#mode=edit) to visualize your code step-by-step
  
  2. Run your code directly inside your web browser's JavaScript console (see our **4 min video on the console in Chrome: https://youtu.be/O_sJE_3jKZ4**)
  
  3. We'll also use [**Glitch**](https://glitch.com/) to collaboratively edit the same code, in real time!
  
  > Glitch also lets us create, test, and share web apps using HTML, CSS, and JavaScript files all within the web browser (see our **6 min video introducing Glitch: https://youtu.be/juqFTEoHN2Q**)

<hr/>

## Challenge 1: 

Run the following code, and then be sure to check your browser's JavaScript console to see what happens!

```javascript
// Create a new variable
let myNerdyJoke = "Debugging is like being the detective in a crime drama where you are also the murderer";

// Display it in the console
console.log(myNerdyJoke);
```

You'll see that `console.log()` allows us to display the value of a variable inside the web browser's console! This is a *very* useful tool for developers to see what's going on inside the code, since we can't see the computer's memory directly.

  > If you didn't use `console.log()`, the variable would be stored in memory, but we wouldn't see it appear anywhere.

<br/>

## Challenge 2: 

Let's take the code from the previous challenge and ***break it five different ways***!

<br/>

**Then discuss** *(in other words, take random guesses and talk about your ideas!)*:

  1. Which words or symbols can we *change* without breaking the code?
  
  2. Which words/symbols need to stay the same?

  3. Does the *order* matter for which of these two lines of code runs first? Why or why not?

<br/>

## Challenge 3: 

A message should appear in the browser console, but the code is broken! Let's fix it up:

```javascript
lot veryTrueStatement = "If you give someone a program, you will frustrate them for a day; if you teach them how to program, you will frustrate them for a lifetime!";
console.log(veryTrueStatement);
```

<br/>

## Challenge 4: 

This code isn't working either. :( Can you fix it so that the joke will appear in the browser console?

```javascript
let coderJoke = "My software never has bugs. It just develops random features.";
Console.log(coderJoke);
```

<br/>

## Challenge 5: 

I found a great joke [from the creator of Stack Overflow](https://twitter.com/codinghorror/status/506010907021828096) but the code below isn't showing the joke in the console like it's supposed to! Can you fix it?

```javascript
let anotherJoke = "There are two hard things in computer science: cache invalidation, naming things, and off-by-one errors."
console.log("anotherJoke");
```

<br/>

## Challenge 6: 

I could've sworn that computers were good at math, so why isn't my code working? Fix all the code below to make the computer actually *add up the numbers* and displays each result in the console:

```javascript
// The answer should be 9, unless the rules of addition have changed since I finished school?!
console.log("4" + "5");

// Last time I checked, 2 + 2 was 4! What's going on here?
console.log("2" + 2);

let x = 1;
let y = 2;
let z = 3;
// The code below is supposed to display the number 6
console.log('x' + 'y' + 'z');
```

**Discuss:**

  1. Why did the broken code work the way it did?
  2. Why are computers so stupid?
  3. Does it matter whether we use single or double quotation marks?

<br/>

## The `+` sign: addition and concatenation!

So it turns out that in JavaScript, the plus sign (`+`) is used for two different things: adding numbers and combining words!

In computer science jargon, we use the word ***string*** to refer to any data that should be treated as a word, a label, or literally a bunch of letters and symbols *strung* together like [those alphabet beads that you can *string* together into a necklace](https://www.etsy.com/market/alphabet_beads)!

Here's another fancy word that will make you sound like a computer scientist: ***concatenation***. It means "chaining things together", just like making a necklace from alphabet beads. So when we write `"hello" + " world!"` in our code, we're *concatenating* the two strings `"hello"` and `" world!"` to create one longer string! In this context, the plus sign (`+`) is called the *concatenation operator*.

<br/>

## Challenge 7: 

Create **three variables** of your own to represent **your name**, **your favorite food**, and **your favorite number**. Be sure to give your variables descriptive names, and use [**camelCase style**](https://en.wikipedia.org/wiki/Camel_case) (where `variableNamesLookLikeThis`, which is the most common convention among JavaScript programmers).

Next, **display a message in the browser's console** that combines each of your three variables into a sentence where you awkwardly introduce yourself by saying something like `"Hi there! My name is Liz, my favorite food is chocolate, and my favorite number is 42!"`

<br/>

## Challenge 8:

Complete the unfinished code below to update the variable named `bugsSolvedToday` to become the **sum of its previous value plus one**, but *without modifying the code already provided below*:

```javascript
let bugsSolvedToday = 7; // Don't modify this line of code!

// Write ONE line of code here (between the others) to solve this challenge:


console.log(bugsSolvedToday); // Don't modify this line either!
```

If you solve it correctly, you should be able to copy-paste that new line of code several times (*without changing it!*) to keep increasing the number by 1 each time.

<br/>

## Bonus challenge:

Similar to the previous challenge, complete this unfinished code to *concatenate* the string `" and again"` onto the end of the variable named `neverEndingSentence`, and then *copy-paste* that line of code to repeat it 10 more times! (Again, don't modify the first or the last line of code provided below.)

```javascript
let theCoderLife = "Debug it again"; // Don't modify this line of code!

// Write a line of code here (between the others) to solve this challenge:

// ...and then copy-paste that line of code 10 more times here to make the string longer and longer:

console.log(theCoderLife); // Don't modify this line either!
```

<br/>
<hr/>

:trophy: ***Great job!*** **Next up:** we'll practice using JavaScript to interact with the web page using the browser's built-in Document Object Model API!

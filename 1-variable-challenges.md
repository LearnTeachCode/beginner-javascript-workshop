# Part 1: Variables and data types

Time to tinker with code and break stuff! Below are several practice challenges where you either need to solve a bug, *create* a bug, or write some code from scratch.

:trophy: For all of these challenges, the goal is ***have fun!*** It doesn't matter if you're correct or not. Like they say, we learn more from our failures than from our successes. So let's have fun "failing", breaking things on purpose, and learning from the experience!

**We'll be using the following tools to run and test our code today:**

  1. Use [**Python Tutor**](http://pythontutor.com/javascript.html#mode=edit) to visualize your code step-by-step
  
  2. Run your code directly inside your web browser's JavaScript console (see our **4 min video on the console in Chrome: https://youtu.be/O_sJE_3jKZ4**)
  
  3. We'll also use [**Glitch**](https://glitch.com/) to collaboratively edit the same code, in real time!
  
  > Glitch also lets us create, test, and share web apps using HTML, CSS, and JavaScript files all within the web browser (see our **6 min video introducing Glitch: https://youtu.be/juqFTEoHN2Q**)

<hr/>

## First: How to open your web browser's JavaScript console

:tv: You can also review our **4 min video on the console in Chrome: https://youtu.be/O_sJE_3jKZ4**

<br/>

**Keyboard shortcuts to open your browser's console:**

|  | Chrome | Firefox | Safari |
| --- | ---- | ---- | ---- |
| **Windows:** | Ctrl + Shift + J | Ctrl + Shift + K | |
| **Mac:** | Cmd + Opt + J | Cmd + Opt + K |  Cmd + Opt + C |

<br/>

Once your browser console is open, it should look something like this in the Chrome browser:

![consoleexample](https://user-images.githubusercontent.com/1555022/40752516-b9c6f472-6424-11e8-9d9c-c49a86ecac1a.png)

<br/>

<hr/>

## Setup for group challenges

:star: [**Click here to open our shared Glitch project**](https://glitch.com/edit/#!/join/90ae8166-64f3-486f-9821-f2a725c842ee), where we'll all be writing code together for our first couple of challenges!

  > Glitch lets us write code together in real time, so we can see each other typing at the same time (just like Google Docs)!

Then be sure to click on `script.js` (in the left-side menu) to look at our JavaScript file.

<br/>

<hr/>

## Group Challenge 1: 

Let's run the following code, and then be sure to check your browser's JavaScript console to see what happens!

```javascript
// Create a new variable
let myNerdyJoke = "Debugging is like being the detective in a crime drama where you are also the murderer";

// Display it in the console
console.log(myNerdyJoke);
```

<br/>

You'll see that `console.log()` allows us to display the value of a variable inside the web browser's console! The code `console.log("hi")` would display the following inside your browser's console:

![console-hi](https://user-images.githubusercontent.com/1555022/40753351-82252724-6428-11e8-857f-3acfa62ab270.png)

<br/>

This is a *very* useful tool for developers to see what's going on inside the code, since we can't see the computer's memory directly. If you didn't use `console.log()`, the variable would be stored in memory, but we wouldn't see it appear anywhere.

<br/>

**Your challenge:** Create a new variable that contains a short sentence to introduce yourself, and then log it to the console!

  > Note: Every variable name needs to be *unique*.

<br/>

## Group Challenge 2: 

Let's take the code from the previous challenge and ***break it several different ways***!

<br/>

**Then discuss** *(in other words, take random guesses and talk about your ideas!)*:

  1. Which words or symbols can we *change* without breaking the code?
  
  2. Which words/symbols need to stay the same?

  3. Does the *order* matter for each of our two lines of code? Why or why not?  

<br/>

## Challenge 3: 

:star: ***For these next challenges, write your code directly in the browser's console.***

A message should appear in the browser console, but the code is broken! Let's fix it up:

```javascript
lot veryTrue = "Using a program: frustrating for a day. Learning to program: frustrating for a lifetime!";
console.log(veryTrueStatement);
```

<br/>

## Challenge 4: 

I found a great joke [from the creator of Stack Overflow](https://twitter.com/codinghorror/status/506010907021828096), but the code below isn't showing the joke in the console like it's supposed to! Can you fix it?

```javascript
let anotherJoke = "There are three hard things in coding: naming things, and off-by-one errors."
console.log("anotherJoke");
```

<br/>

## Challenge 5: 

I could've sworn that computers were good at math, so why isn't my code working? Fix all the code below to make the computer actually *add up the numbers* and display each result in the console:

```javascript
// The answer should be 9, unless the rules of addition have changed since I finished school?!
console.log("4" + "5");

// Last time I checked, 2 + 2 was 4! What's going on here?
console.log("2" + 2);
```

**Discuss:**

  1. Why did the broken code work the way it did?
  2. What's the difference between `2` and `"2"`?
  3. Why are computers so stupid?

<br/>

## The `+` sign: addition and concatenation!

So it turns out that in JavaScript, the plus sign (`+`) is used for two different things: adding numbers and combining words!

In computer science jargon, we use the word ***string*** to refer to any data that should be treated as a word, a label, or literally a bunch of letters and symbols *strung* together like [those alphabet beads that you can *string* together into a necklace](https://www.etsy.com/market/alphabet_beads)!

<br/>

:star: Here's another fancy word that will make you sound like a computer scientist: ***concatenation***.

It means "chaining things together", just like making a necklace from alphabet beads. So when we write `"hello" + " world!"` in our code, we're *concatenating* the two strings `"hello"` and `" world!"` to create one longer string! In this context, the plus sign (`+`) is called the *concatenation operator*.

<br/>

## Challenge 6: 

The code below should display this sentence in the console: `"Hello, my name is Bob Loblaw and I write the Bob Loblaw Law Blog!"`. But it's not working... Can you fix it?

```javascript
let myName = "Bob Loblaw";
let myHobby = "writing the Bob Loblaw Law Blog";

console.log("Hello, my name is" + myName + and I myHobby + "!";
```

<br/>

## Challenge 7:

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

## Group review:

:star: [**Click here to open our shared Glitch project again**](https://glitch.com/edit/#!/join/90ae8166-64f3-486f-9821-f2a725c842ee) to review and practice a bit more together!

<br/>
<hr/>

:trophy: ***Great job!*** **[Next up: Interacting with the web page (Document Object Model)](https://github.com/LearnTeachCode/beginner-javascript-workshop/blob/master/2-dom-challenges.md)**

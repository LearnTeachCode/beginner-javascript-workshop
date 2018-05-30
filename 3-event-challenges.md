# Part 3: Events and event listeners

:point_left: ***[Previous section: Interacting with the web page (Document Object Model)](https://github.com/LearnTeachCode/beginner-javascript-workshop/blob/master/2-dom-challenges.md)***

Events and event listeners allow you to respond to user input (among many other types of events), telling a section of your code to *wait* until a particular event occurs, and then execute one of your functions when triggered by the event.

Web browsers provide a built-in JavaScript function named `document.addEventListener()`, which is available on any DOM element in JavaScript -- so *any* element of the web page can respond to various actions from the user!

<hr/>

## First, an example:

Before we dive in, try out this example of an event listener by copy-pasting the code below and running it directly in your browser console (on *any* web page):

```javascript
document.body.addEventListener("click", logClick);

function logClick () {
  console.log("This message should appear in the browser console!");
}
```

After running the code... nothing happens! Why's that? 

*...because the event hasn't been triggered yet!* 

To trigger the event, click anywhere on the web page. Then look inside the console. You should see a message show up in your console when you click!

<br/>

## Three parts for setting up event listeners

Every time you use an event listener, there are **three main questions** you'll need to answer:

  1. **Where is the event happening?** Here, it's happening anywhere in the `document.body` (the `<body>`, the entire web page!)
  2. **Which event are we listening for?** Here, it's a `"click"` event ([see the list of all built-in events here!](https://developer.mozilla.org/en-US/docs/Web/Events))
  3. **What should happen when the event occurs?** Here, we run our function named `logClick`

<br/>

## Challenge 1:

For these next challenges, **remix this Glitch project: https://glitch.com/edit/#!/dragon-defeater-v0-starter**

**Your first step:** Copy-paste the code from the example at the top of this page, and test it to make sure the code works!

<br/>

## Challenge 2:

Using what you learned in our previous set of challenges, add one more additional line of code so that when the user clicks on the page, **the entire body of the document** will be replaced with the text `"You clicked on the page!"`.

<br/>

## Challenge 4:

Modify your code for the previous challenge so that when the user clicks on the page, instead of overwriting the *entire page*, your code will only overwrite the text inside the paragraph with the **ID of `"outcome"`**.

<br/>

## Challenge 5:

For this game, the user should only be able to click on the *button*, not the entire page! Change the first part of your code so that the event listener is only "listening" on the button itself.

  1. First, you'll need to look in the HTML file to see how to identify the button!
  
  2. Then you'll need to *switch out* the piece of your code that represents the whole body of the web page, and *replace* it with some code that represents the button.

<br/>

## Bonus challenge:

There are *lots* of built-in events that web browsers provide for you to use in your code!

Take a look at [this reference page listing *all* the built-in web browser events](https://developer.mozilla.org/en-US/docs/Web/Events), and **change your code** from the previous challenge so that your function is instead triggered when the user **double clicks** on the page.

<br/>

## Group coding challenge:

Let's work on building this game together! **Open this link and then *click the link at the top of the page* to code with us: https://dragon-defeater-v0-group.glitch.me/**

<br/>

:hammer: **First, what are we building?** Let's create one of the simplest video games ever invented: **a click-counter game!** Yes, there's an entire genre of games where the sole purpose is to click a button as many times as you can. (Usually there's a time limit, but we'll leave that out for now.)

**Feature requirements:**

  - There should be a button that the user can click on.
  - And there should be a paragraph that says how many times the button was clicked.
  - Every time the user clicks that button, the number of clicks should increase by one, and that new number should be displayed in the paragraph described above.
  - Initially, that paragraph should say that the button was clicked **0** times.
  - ... and that's all!

We'll need to use *all* of the building blocks we've learned how to use so far.

<br/>

<hr/>

:trophy: ***Woohoo!*** You're well on your way to mastering JavaScript and the basics of web development! This was only the tip of the iceberg of course, but you gotta start somewhere. :)

Never stop tinkering, never stop breaking things, never stop building things! Go forth and code!

# Practice challenges: Interacting with the web page (Document Object Model)

:bulb: The ***Document Object Model (DOM)*** refers to how the web browser sees a web page -- as a *hierarchy* of objects, each with its own set of characteristics (like the text inside it, the font, the color, etc). We use the term ***DOM element*** to refer to pieces of the web page like a paragraph (`<p>`), an image (`<img>`), a heading (`<h1>`), etc.

Let's use JavaScript to access the **DOM** and modify the HTML and CSS of some web pages! For the following challenges, you'll be using the Glitch links provided to test out some example code, fix some bugs, and create some bugs of your own.

<hr/>

## How to use Glitch

**Instructions:**

  - To **remix** a project on Glitch, click the project's name in the top left corner, and then click "Remix This" in the dropdown menu to make your own personal copy.
  
  - **To see the live app and test it out**, click "Show Live" on the top left and it'll open the web page in another tab.

  - Remember to check *both* the **live web app** and the **JavaScript console in Chrome's developer tools** to see the results of your code, hunt down any bugs, and check if you've fixed those bugs!

![glitchscreenshot](https://user-images.githubusercontent.com/1555022/40146036-e95ba9ec-5918-11e8-9533-094d6f8d858e.png)



<br/>

## Challenge 1:

For these first three challenges, **remix this Glitch project: https://glitch.com/edit/#!/js-challenge-123**

Notice the following:

  - The `index.html` file has some paragraphs with text.
  - But if you look at the live web page (click "Show Live" inside Glitch), that's not the text you see on the screen!

**Your challenge:** Which file and which line number is creating the text that you see on the live web page?
 
<br/>

## Challenge 2:

In that same Glitch project, **change the code** so that the web page will now show the message: `"Hello world! I know how to use JavaScript!"`

<br/>

## Challenge 3:

Let's hack Google! (Well... not really, but sort of!)

  1. Copy that one line of JavaScript code from the previous challenge.
  2. In a new browser tab, go to Google.com
  3. Then open your browser's JavaScript console while you're on that page.
  4. Paste that line of JavaScript code into the console, and press Enter to run the code!

<br/>

What happened to the web page? (Pretty cool, right?)

  > But what happens if you refresh the web page?

<br/>

## Challenge 4:

For this challenge, **remix this Glitch project: https://glitch.com/edit/#!/js-challenge-4**

<br/>

First: how is this code different from the code in the previous challenge?

<br/>

Next, **your challenge:** 

  - Make *another* paragraph in the HTML file with its own unique ID.
  - Write *another* line of JavaScript code to replace the text of your new paragraph

<br/>

## Selecting specific elements of the web page

The `document.getElementById()` function in JavaScript takes **one input**: the ID of whichever HTML element you want to access. For example, to change the text inside that example paragraph with the ID of `"special"`, we can do this:
  
```javascript
document.getElementById("special").textContent = "This text will overwrite the text of a special paragraph.";
```

<br>

Notice how the `document.getElementById()` function is ***interchangeable*** with `document.body` in JavaScript code:

```javascript
// Using body
document.body.textContent = "This replaces the text of the entire body element.";

// Using the getElementById() function
document.getElementById("special").textContent = "This replaces the text of that special paragraph.";
```

<br>

:bulb: Switching out interchangeable pieces -- like Lego blocks! -- is one of the most fundamental concepts in every programming language. Coding is all about recognizing *which* pieces can be swapped out, *where* they can and can't be used, and *how* to mix and match them to create new things!

<br>

## Challenge 5:

For these next two challenges, **remix this Glitch project: https://glitch.com/edit/#!/js-challenge-56**

**Your challenge:** Take a look at the code for this project. There's a bug! Can you fix it?

  > **Hint:** Be sure to check the live web page, the browser console, the HTML file, and the JS file!

<br/>


## Challenge 6:

Next, write three more lines of code in the JavaScript file to accomplish the following:

  1. Change the text of the **red** box to say `"Beep!"`
  
  2. Change the text of the **green** box to say `"Kaboom!"`
  
  3. Change the page heading to say `"I am a JavaScript Jedi Master!"` (Hint: look for the `<h1>` tag in the HTML)

<br/>


## Bonus challenge:

This is a Google challenge! Look online to figure out how to ***change the background color*** of the entire web page, and test it on *any* live website by running the code directly in your browser console. Try it on [Google.com](https://www.google.com/), for example!

<br/>

<hr/>

:trophy: ***Great job!*** **Next up:** ......

# JavaScript
JavaScript forms part of Front-End Web Development. 
JavaScript is the foundation upon which the modern web has continued to expand and evolve. It powers the modern web, servers, and even the development environments on desktops.
HTML is the language of web structural content
CSS is the language of web display or style
JavaScript is the language of web interaction
Meta/Facebook particularly created React, one of the most popular front-end frameworks. 
Node.js ensures fast matching riders and drivers, as well as quick iterations.
You need one of the following tools on your PC to use javascript I will be using Chrome but you can also use Firefox or Edge. Tou also need VS code
we are particularly interested in the console. It can be accessed by clicking the console option or by hitting the “Escape” button on your keyboard. This action will both open and close the console.
From this console, you can directly interact with the JavaScript on the page. This will all be covered in more detail later. For now, make sure you have: 
A modern browser
A code editor
A live server environment
Know how to gain access to the console in the web browser.
Vanilla Javascript or Javascript proper.
First off, at the core of all of this sits JavaScript itself, often colloquially referred to as Vanilla JavaScript. This is the scripting language itself and the scripting language for the web. This is what you write when you write JavaScript and what will be covered in this course. Everything else is built on top of JavaScript itself, Vanilla JavaScript or JavaScript Proper.
ECMA Script
The browser implementation specification for JavaScript is called ECMAScript
ECMAScript is not the language itself, but the official description of how the language should be interpreted by browsers.when you write JavaScript, it behaves the same way no matter what browser is used.When people write some version of ECMAScript, they typically use a tool called Babel to convert their code back into JavaScript the current browser can read.
TypeScript is heavily used in modern JavaScript frameworks and you can usually spot TypeScript by looking at the file name. TypeScript files typically have the .ts file name extension. Think of TypeScript and CoffeeScript and all other variations of JavaScript as dialects of JavaScript. JavaScript is an opinionated coding language. TypeScript files typically have the .ts file name extension.
JavaScript frameworks-The modern web runs on JavaScript frameworks. These are tools written in JavaScript to render content on the web in the form of applications. The most popular of these frameworks are React or React.js, Vue or Vue.js, and Angular or AngularJS. They all add an abstraction layer on top of JavaScript to do things in a more streamlined and efficient way. For example, React uses JSX or JavaScript XML which simplifies how we mix JavaScript and HTML.  JavaScript frameworks come with build tools. These are helper applications, typically automated, that run on your computer or on the cloud to turn your human-written and readable JavaScript code into code optimised for the browser. Babel has already been mentioned. Other common tools include NPM, WebPack, Grunt, Gulp and so on.
Server runtime NODE JS-JavaScript has migrated from the browser to the server, and now you can write JavaScript to run on the back-end as well as the front-end of applications. Node.js is the ubiquitous JavaScript server runtime used for this purpose. When you work with modern JavaScript, you will be interfacing with Node.js on your computer all the time, through the Node package manager or NPM.
pRETTIER-this makes formatting the code visually more presentable.
ESLint-This is sort of like spellcheck but for JavaScript.It ensures the code is consistent.

Sample Starter Code:


<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <title>My First JavaScript Page</title>

  <script src="script.js"></script>

</head>

<body>

  <h1>Hello, World!</h1>

</body>

</html>
Write JavaScript from top to bottom because that is how the browser will read it.
To leave a single-line comment in JavaScript, you use two forward slashes [//] followed by a string of text like this example: // Single line comment
Note:  Everything behind the two forward slashes will be treated as a comment. You can do that on its own line or you can also do it inside another line of code
If you need multiline comments, you use CSS comment syntax i.e. forward slash asterisk to start the multiline and asterisk forward slash to end then the comment. You can add as many lines of text as you want in between these two markers. /* comment*/
If you are using a code editor like VS Code, there is also a shorthand for a more verbose type of comment. Look at the following example: here is a function called updates backpack and if you enter forward slash, two asterisks, and then hit return, VS Code will create a verbose comment and even capture that this function has a parameter called update.
/**
*
*@param {*} update
*/
Where do you actually write the JavaScript code? There are several different approaches to storing and serving JavaScript in an HTML document. Most prominently inline, meaning the JavaScript itself is literally in line inside the document and saved as an external file. In the exercise files for this movie 02_01, you will find index.HTML and which is an entirely self-contained HTML document that has both styles and JavaScript inline. 
Right before the </body> tag, we have a <script> tag with JavaScript inside, followed by an </script> tag. This script tag is how you add JavaScript to a document.
















# Lecture 1

## What is JavaScript?

JavaScript is a high-level, interpreted programming language that conforms to the ECMAScript specification. JavaScript has curly-bracket syntax, dynamic typing, prototype-based object-orientation, and first-class functions.

## What is ECMAScript?

ECMAScript is the scripting language specification that JavaScript is based on. It is standardized by the ECMA International standards organization.


## Ways to run JavaScript:

1. **Browser Console**: Open the browser console by pressing `F12` and then go to the `Console` tab. You can write JavaScript code directly in the console and run it by pressing `Enter`.

2. **Node.js**: You can run JavaScript code on your computer using Node.js. To do this, you need to have Node.js installed on your computer. You can download Node.js from the official website: [Node.js](https://nodejs.org/). Once you have Node.js installed, you can create a JavaScript file with your code and run it using the `node` command in the terminal. For example, if you have a file called `script.js` with your code, you can run it using the following command:

```bash
node script.js
```

## What is Node.js?

Node.js is an open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside of a browser. Node.js lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser.


## How to view the output of JavaScript code on the browser?

You can view the output of JavaScript code on the browser by using it in an HTML file. Here is an example of how you can do this:

```html
<!DOCTYPE html>
<html>
<head>
    <title>JavaScript Example</title>
</head>
<body>
    <h1>JavaScript Example</h1>
    <p id="output"></p>
    <script>
        document.getElementById("output").innerHTML = "Hello, World!";
    </script>
</body>
</html>
```

In this example, the JavaScript code sets the content of the `output` paragraph element to "Hello, World!".

## Keywords in JavaScript:
1. **var**: The `var` keyword is used to declare variables in JavaScript.
2. **let**: The `let` keyword is used to declare block-scoped variables in JavaScript. 
3. **const**: The `const` keyword is used to declare constants in JavaScript. 
4. **function**: The `function` keyword is used to define functions in JavaScript.
5. **return**: The `return` keyword is used to return a value from a function in JavaScript.
6. **if**: The `if` keyword is used to execute a block of code if a condition is true in JavaScript.
7. **switch**: The `switch` keyword is used to execute a block of code based on different cases in JavaScript.
8. **for**: The `for` keyword is used to create a loop that executes a block of code a specified number of times in JavaScript.
9. **try**: The `try` keyword is used to start a block of code that will be tested for errors in JavaScript.


### My Notes:
- In JavaScript, the window object is the global scope object. This means that variables, properties, and methods by default belong to the window object. This also means that specifying the window keyword is optional:
- For debugging purposes, you can call the console.log() method in the browser to display data.
- The var keyword should only be used in code written for older browsers.
- You cannot re-declare a variable declared with let or const.
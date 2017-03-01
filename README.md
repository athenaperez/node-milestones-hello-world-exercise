# node-milestones-hello-world-exercise
Node Milestones, Foundations, Exercise 1

Hello, World!

Introduction

Node.js is a runtime environment for developing applications in JavaScript outside of the browser. Node.js is most commonly used in a command-line interface to build command-line applications or web servers. After installing Node.js, you are able to execute a JavaScript file with Node.js using the node command followed by the name of the file.

Example:

node myJavaScriptFile.js
The JavaScript contained in the file executed in a Node.js environment should be similar to a JavaScript file written for the browser. You have access by default to all of JavaScript's primitives, standard libraries like Math and Date, and newer versions of Node.js include many ES6/ES2015+ features like Template Literals, Arrow Functions, and Destructuring. (oh, yeah!)

However, since there isn't a visual interface defined in Node.js, there are some things that you may be used to being available in a browser, but are not available in Node.js. These features are called Web APIs.

For example, in a browser environment, there is a global document object that has methods for interfacing the Document Object Model (DOM). Without a visual interface, the DOM is not available so this object does not exist.

Additionally, in a browser, you can create an alert popup box with alert('This is an alert message'). Again, since there is no ability to "popup" in the terminal, the alert function is not available.

One feature that is commonly used for feedback of command-line applications written in Node.js is the console methods like console.log. While the global console object is considered a Web API, it has been reimplemented in Node.js for convenient access to the terminal output. In other words, it works pretty much exactly like it does in the front-end, but it outputs to your terminal, not your dev tools' console. It uses the terminal's standard output stream, which we will talk about very soon.

Adding the operation console.log('This is a log message') will output This is a log message to the terminal through the stdout interface along with an invisible Newline character \n for any additional commands that may follow.

Requirements

For this exercise you will create a Hello World program.

Create a JavaScript file to act as a Node.js program named hello-world.js. The file should contain JavaScript code to output the phrase "Hello, World!" to the terminal through the stdout stream.

Expected:

$ node hello-world.js
Hello, World!
Additional Reading

Node.js
Node's creator introduces Node.js
Command-line interface
Node.js ES2015 Support
JavaScript Web APIs
Console object
Standard streams
Newline
Hello World program

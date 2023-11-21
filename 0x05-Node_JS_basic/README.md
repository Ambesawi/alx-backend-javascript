# 0x05. NodeJS Basics

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- Run JavaScript using NodeJS
- Use NodeJS modules
- Use specific Node JS modules to read files
- Use process to access command line arguments and the environment
- Create a small HTTP server using Node JS
- Create a small HTTP server using Express JS
- Create advanced routes with Express JS
- Use ES6 with Node JS with Babel-node
- Use Nodemon to develop faster

## Requirements

- Allowed editors: vi, vim, emacs, Visual Studio Code
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using node (version 12.x.x)
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the js extension
- Your code will be tested using Jest and the command npm run test
- Your code will be verified against lint using ESLint
- Your code needs to pass all the tests and lint. You can verify the entire project running npm run full-test
- All of your functions/classes must be exported by using this format: module.exports = myFunction;

## Provided Files

- database.csv

- package.json

- babel.config.js

- .eslintrc.js

## Instructions

Don’t forget to run `$ npm install` when you have the package.json

## Tasks
## Table of Contents
1. [Task 0: Executing basic javascript with Node JS](#task-0)
2. [Task 1: Using Process stdin](#task-1)
3. [Task 2: Reading a file synchronously with Node JS](#task-2)
4. [Task 3: Reading a file asynchronously with Node JS](#task-3)
5. [Task 4: Create a small HTTP server using Node's HTTP module](#task-4)
6. [Task 5: Create a more complex HTTP server using Node's HTTP module](#task-5)
7. [Task 6: Create a small HTTP server using Express](#task-6)
8. [Task 7: Create a more complex HTTP server using Express](#task-7)
9. [Task 8: Organize a complex HTTP server using Express](#task-8)

### 0. Executing basic javascript with Node JS

In the file `0-console.js`, create a function named `displayMessage` that prints in STDOUT the string argument.

```javascript
// 0-main.js
const displayMessage = require('./0-console');

displayMessage("Hello NodeJS!");
$ node 1-stdin.js
Welcome to Holberton School, what is your name?
Bob
Your name is: Bob
This important software is now closing


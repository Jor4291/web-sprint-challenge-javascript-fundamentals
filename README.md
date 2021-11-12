# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

    .map takes all of the items in an array, changes them, and pushes them to a new array.

        - You could use this to change all the names in a directory to have capitalized letters instead of lowercase.

    .filter takes all of the items that you've passed as an argument with .filter() and returns them in a new array

        -You can use this to go through a large array of data and return a specific item from each element. If you had an array of baseball players you could use .filter to return players with a certain batting average.

    .reduce iterates over an array and collects all of its elements into a single result

        - You can use this to iterate over an array of numbers and return a total like adding the prices of groceries on a grocery list

2. Explain the difference between a callback and a higher order function.
    A function that takes in a function or returns a function is considered a higher order function. The function we insert is the callback function.

3. Explain what a closure is.
    closure makes it possible for a function to have restricted variables that stay within its scope. When functions become nested its the closure that keeps the code from applying to other blocks.

4. Describe the four principles of the 'this' keyword.  

    1.) Window/Global Object Binding - When in the global scope the value of "this" will be the window/console.

    2.) Implicit Binding - When a "." calls a function, the object before the "." is "this".

    3.) New Binding - When using a constructor function, "this" refers to the specific instance of the object that has been created and returned by the constructor function.

    4.)Explicit Binding - When we use the call or apply methods, "this" is explicitly defined.

5. Why do we need super() in an extended class?

    The "super()" method allows us to call the parent's constructor method and get access to the parents properties and methods. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://lambdaschool.notion.site/lambdaschool/Lambda-School-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade

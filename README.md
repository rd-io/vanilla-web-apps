# Vanilla Web App Collection
---

## Fundamentals Of Web Dev
This repository is a test bed of only using vanilla tools to make websites and web apps. This contains three separate projects that can be expanded on if needed.

### - To-Do Vanilla
- Using only HTML, CSS, and JavaScript, a simple to-do application that can have items added, marked as completed, and removed.
- To-do items are currently stored in *session storage* for the purpose of this project. When closing the browser tab running this web app, or closing the browser, the session storage will remove itself.
  - By default, I do not want persistent storage for this education project on your computer.
  - If you want to use local storage, replace every instance of `sessionStorage` with `localStorage` in this project's `script.js` file, and the To-Do items will persist even if the tab running this app, or the browser itself, is closed.

### - Calculator Vanilla
- Using only HTML, CSS, and JavaScript, a simple calculator that can perform basic math operations: addition, subtraction, multiplication, and division.
 - All logic is coded by me, to parse a mathematical expression, then solve it using the order of operations, inspired by the funcitonal programming paradigm.

### - Node.js Routing
- No frameworks, such as Express.js, were used. This is used to serve static web pages to the user. Navigation between the calculator and to-do list is possible through these routes.

---
<br>

## Why Make These Tools?
Every single developer is expected to know how to make a to-do list and a calculator. This is my creation of simple web apps that developers are expected to know how to make.

## Why use Vanilla HTML, CSS, JavaScript, and Node?
Before allowing myself to use tools that make development easier, such as React, Express.js, or any other commonly used Node packages, I would like to make these myself when possible.
The purpose of these applications is to learn why these frameworks exist, and the problems that they solve, by experiencing the common difficulties with using vanilla tools.

## This Project is Complete
After finishing the to-do and calculator apps, and getting Node.js to work in serving these static pages, I consider this project finished. Additional apps can be added if desired.
For now, I am needing to concentrate on becomming proficient with frameworks to get a job.

# Transitioning to Unit 2

## Overview

Congratulations! You've just cleared Unit 1. Before we get to Unit 2, here are some helpful resources to help ground the stuff you'll need to move forward, as well as give you a look as to what we're learning. The only required part of this is under the [requirements](#requirements) section. Everything else is helpful and optional reading.

## Requirements

#### Web Browsers

Before we start Unit 2, it is imperative that you download and use Chrome for development, as [61% of web browser users](https://www.w3counter.com/globalstats.php) use Chrome. This is both to create a mutual environment for all developers in the course, as well as understanding the standard development environment for front-end development.

#### React DevTools

After downloading Chrome, install the [React DevTools extension](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en) to Chrome. This will give you access to see what's happening inside of your React applications as we progress through Unit 2. 

#### Addressing Wi-Fi Troubles

In the age of the remote classroom, it's important that we're able to accomodate those with poor internet connection. As a result, we can use a great NPM package developed by Netflix to test our internet speeds each morning. Go to your command line and type the following command, and press enter:

```sh
npm install --global fast-cli
```

This will install __Fast__ globally, so you can use it from any folder. To use it and test your download/upload speed, run the following command (the -u includes upload):

```sh
fast -u
```

#### Skill Assessment

[Create a new issue ticket](https://git.generalassemb.ly/sei-nyc-dragonflies/unit-2-transition/issues) on this repository, and rate your comfort with the following subjects from 1 (I don't know where to start) to 5 (I could teach this). If your answer is a 3 or below, add a blurb about what you feel you don't understand.

- Arrays
- Objects
- DOM Manipulation
- Events
- Array Methods
- AJAX and HTTP
- Axios
- Async and Await

## Developing Great Habits for the Industry

#### Typing Speed

Now that we've been coding consistently for three weeks, it's understandable to feel like you want to code faster. An easy to way to do this without having to develop more knowledge on any given subject is by __increasing your typing speed__. A great way to do this is by learning __touch typing__! I highly recommend typingclub, a free typing program for all ages. Getting ten minutes of practice in the morning will warm up your fingers to make some great code!

- [Typing Club](https://www.typingclub.com/)
- [Typing.io](https://typing.io/) (a programmer focused typing practice site)

#### Git Help

Feeling weird about Git? Check out these resources for additional information and extra guidance for being version control masters!

- [Git Explorer](https://gitexplorer.com/)
- [A Gentle Introduction to Git and GitHub](https://hackernoon.com/a-gentle-introduction-to-git-and-github-the-eli5-way-43f0aa64f2e4)

## Re-establishing Concepts

#### Array Methods

We're going to be using a lot of array methods (which we'll review during this next unit). One you may have seen before is __forEach__. The main three to be aware of for our next unit are __map__, __filter__ and __reduce__. The callback functions for these will be in __arrow function__ form. These will be our bread and butter when we approach React. Here are some good resources to review:

- [Arrow Functions on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
- [Arrow Functions on YouTube](https://www.youtube.com/watch?v=h33Srr5J9nY)
- [.map() on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
- [.filter() on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- [.reduce() on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
- [.map() on Codeburst](https://codeburst.io/learn-understand-javascripts-map-function-ffc059264783)

#### JavaScript Events

When we want to update a particular input or submit a form, the Event class is triggered. React also capitalizes on JavaScript events, but instead of using .addEventListener, we'll be able to use event-specific functions. Here are some great resources to review on JavaScript events:

- [Introduction to events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
- [Event reference on MDN](https://developer.mozilla.org/en-US/docs/Web/Events)
- [JS Events on W3Schools](https://www.w3schools.com/js/js_events.asp)

## Reading Ahead

If you want to find out more about what we're learning moving forward, check out the following resources about React, Node, and NPM:

- [Getting Started with React](https://reactjs.org/docs/getting-started.html#try-react)
- [What is React (in 5 Minutes)](https://www.youtube.com/watch?v=N3AkSS5hXMA)
- [Node.js vs. Browser-Facing JS](https://medium.com/swlh/what-is-node-js-and-how-does-it-differ-from-a-browser-ddebef00cbd9)
- [What is NPM? (npm)](https://nodejs.org/en/knowledge/getting-started/npm/what-is-npm/)
- [What is NPM? (W3Schools)](https://www.w3schools.com/whatis/whatis_npm.asp)

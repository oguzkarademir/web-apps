# Week 1

## Module Name

* [Prep Work](#prep-work)
* [Lesson Plan](#lesson-plan)
  * [Isolate](#isolate)
  * [Integrate](#integrate)
* [Assignments](#assignments)
  * [Exercises](#exercises)
  * [Project](#project)

---

## Prep Work

### Node.js 101

Both of these are long videos, you don't need to finish them before class. But they are great videos! Finish studying them over the next week for gud learns.

* [Mosh](https://www.youtube.com/watch?v=uVwtVBpw7RQ&list=PLTjRvDozrdlydy3uUBWZlLUTNpJSGGCEm&index=1)
* [Traversy](https://www.youtube.com/watch?v=fBNz5xF-Kx4)

---

## Lesson Plan

> [Lesson Plan Slides](https://hackyourfuture.be/module-name/week-X)

* Command line arguments: `argsv`
* Native Node.js modules: `fs`, `assert`

### Isolate

* `assert`: [examples](../isolate/assert)
* `fs` (with callbacks): [examples](../isolate/fs-examples), [exercises](../isolate/fs-exercises)

### Integrate

* [weather-it](../integrate/weather-it)
* [json-todo-cli](https://github.com/hackyourfuturebelgium/coming-soon) (starter repo)

---

## Assignments

> Before getting started on the homework, take a minute to set up your [Homework Issue](https://github.com/HackYourFutureBelgium/homework-submission#homework-issues) on this module's project board.

### Exercises

#### Isolating JavaScript

* [learn-util-promisify](https://github.com/hackyourfuturebelgium/learn-util-promisify)
  * Learn how to convert functions with callbacks to promises using [util.promisify](https://nodejs.org/api/util.html#util_util_promisify_original)
* [node-fetchemon](https://github.com/hackyourfuturebelgium/node-fetchemon)
  * Practice making API calls from Node.js using the [node-fetch](https://www.npmjs.com/package/node-fetch) module

#### Integrating JavaScript

* [cowsaydex](https://github.com/hackyourfuturebelgium/cowsaydex)
  * Practice integrating NPM Packages into your projects, starting with [cowsay](https://github.com/piuccio/cowsay)

### Project

#### `restful-courses`

> [Code-Along](https://github.com/HackYourFutureBelgium/homework-submission/#projects)

This week's project is to follow the  [Build RESTful APIs with Node and Express](https://www.youtube.com/watch?v=pKd0Rpw7O48) by Mosh.  Besides just Express and writing RESTful routes you will learn how to use _JSON schemas_, test your API's with _Postman_, use _environmental variables-, and practice continuous development using _nodemon_.  But that's not enough! After finishing with the tutorial you will need to refactor the code so that:

* It reads and writes from a file called `courses.json` instead of using a local variable.

You will be expected to turn in your code from his tutorial on a new repository called `restful-courses`. you will be assessed not only on your live demo, but also on the quality of your code, the correctness of your branches, the organization of your code, and the completeness of your README.  Your repo must include:

* A `development-strategy.md` file to explain how you built the app in small pieces (this file doesn't need to match the tutorial!)
* One branch per step in your `development-strategy.md`
* A complete README.md

#### Challenge: Deployment

Deploying you project is not required, but is suggested.  This is a nice first project to try out fullstack deployment.

__Directly from GitHub__

* [FCC Article](https://www.freecodecamp.org/news/how-to-deploy-a-nodejs-app-to-heroku-from-github-without-installing-heroku-on-your-machine-433bec770efe/)
* [Heroku CI](https://www.heroku.com/continuous-integration)

__From Terminal__

* [Heroku Getting Started](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
* [Scotch Tutorial](https://scotch.io/tutorials/how-to-deploy-a-node-js-app-to-heroku)
* [Heroku devhints](https://devhints.io/heroku)
* [Heroku DevCenter: Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
* [Heroku DevCenter: Advanced Automation](https://devcenter.heroku.com/articles/multiple-environments#advanced-linking-local-branches-to-remote-apps)
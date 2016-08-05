# pythonicjs
A JS lint plugin to help you write JavaScript in the spirit of the Zen of Python

## What PythonicJS Isn't

 - Python compiled, transpiled, or magic'ed into JavaScript
 - A new set of set of syntax for JavaScript to make it look like Python
 - A library, framework, or middleware to bring the joys of the GIL to the web

## What PythonicJS Is

 - A style guide for ES2017
 - A linter that passes a subset of ES2017 syntax in line with that style guide.
 - A boilerplate project to get you running with ES2017 today.
 - An attempt to make the transition from Python to JavaScript just a little easier.
 - A place for frustrated Pythonistas to share a grail of ale and take a break from the madness of everyday JS

## Why ES2017?

With the advent of Python 3.5 and the upcoming features of ECMAScript 2017 the two languages finally have a core
unifying construct: async/await.

If you've used the wonderful HTTP server library Tornado or anything built on asyncio you're probably familiar with how Python can handle asyncronous programming. In 3.5 that got standardized into the async/await structure we have today.

Javascript, of course, has always needed asynchronous constructs, but for a long time it meant a series of nested callbacks that were, at the best of times, difficult to write, read, and debug. That improved substantially with the introduction of concepts like "deffered", "thenable", Promises and generators, but in the next (next) version of JavaScript we are finally getting the full async/await constructs that allow asynchronous code to be written in a straightforward manner.

There has never been a better time for people who love Python to give JavaScript a try. That said JavaScript is a bit
of the wild west. The features I'm talking about aren't even in the language yet but are being used today. The bleeding edge of the community invents new frameworks and paradigms every year or so, and there's barely any time to understand the possibilities of new features before they are deprecated. This makes being a professional web developer exciting, fast-paced, and a bit nerve wracking. PythonicJS has a different goal. Find a beautiful core to JavaScript, apply a liberal helping of Pythonic philosophy, and stick with it.

You may not be able to write React code that passes for Pythonic, or Angular, or use much of jQuery, but you will be able to write JavaScript that is beautiful, explicit, simple, flat, readable and generally Zen.

## Do I need the boilerplate?

Async / await don't exist in ECMAScript officially yet, and are not generally supported by browsers. It is a definite goal of this project to reduce the boilerplate as time goes on, until you can confidently program pythonic JavaScript without worrying about a compilation step. Until then though you'll need a few extra things to get started and have your code actually *run*.


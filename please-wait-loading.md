# Please wait... loading: a tale of two loaders

## Abstract

Modules were first standardized in [ECMAScript 6](https://www.ecma-international.org/ecma-262/6.0/index.html#sec-ecmascript-language-scripts-and-modules) in 2015. As of December 2017 [you can now use](https://caniuse.com/#feat=es6-module) ESModules (ESM) in 3 out of 4 of the major browsers. Node.js has traditionally shipped an implementation of [Common.js](http://www.commonjs.org/) (CJS), you use it in your Node.js code today via require().

There are vast differences between the two module systems that make it quite difficult to utilize Common.js code in an ESModule and vice versa. Implementing modules correctly in Node.js will have a significant impact on the future of JavaScript, the wrong decisions could cause fractures in the ecosystem. This talk will dive into some of the more nefarious edge cases and the ways the Node.js project has navigated them. The talk will also look into joint efforts with the Web platform as we attempt to find a single pattern that can work on both the client and server.

## A bit more info

The talk will look at the history of modules in the js ecosystem and the subtle difference between them. It will also skim over how ecma-262 is standardized by the tc39, and how esmodules were developed.

## Pitch

ES Modules and Common JS go together like old bay seasoning and vanilla ice cream.

This talk will dig into the inconsistencies of the two patterns, and how the Node.js project is dealing with reconciling the problem. 

## Takeaways

* The differences between CommonJS (cjs) and ESModules (esm)
* Why ESM works the way it does, and why those decisions were made
* Underlying mechanism of how ESM is implemented in the Browser and Node
* How the standards process works and how Modules were made
* The work being done by various parties to avoid ecosystem fracture
* Best practices for choosing a module system today

## Prerequisite Knowledge

Attendees should have a working knowledge of JavaScript and a passing knowledge of CommonJS and ESM. This talk will get into the history and semantics of the patterns, so those who are only somewhat familiar should still get value from this presentation

## Watch the talk

[![JSConf EU 2018](https://img.youtube.com/vi/35ZMoH8T-gc/0.jpg)](https://www.youtube.com/watch?v=35ZMoH8T-gc)

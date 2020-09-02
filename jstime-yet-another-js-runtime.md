# jstime: yet another JavaScript Runtime

## Abstract

jstime is a hyper minimal, extremely embeddable, JavaScript runtime built in rust on top
of "rusty_v8", the rust bindings to the V8 JavaScript engine maintained by the Deno project.

jstime is also the first rust project I've ever worked on. In just a couple weeks the project
has grown from a few lines of code that could print "hello world", to a functional JavaScript
runtime with a working governance model and multiple maintainers.

From learning about lifetime's to implementing rough consensus this talk will cover what's
happened in jstime up until now and the lessons learned along the way.

## A bit more info

There are a lot of different topics that can be covered in this talk, not limited to:

* How JavaScript runtimes work
* V8 architecture
* Getting started with rust
* why rust is a great language for building other programming language runtimes
* What was difficult to grok as a JavaScript developer writing in Rust
* Automating Continuous Integration and Deployment with GitHub Actions
* Automating Releases with cargo-release
* Avoiding a BDFL model in your OSS
* Building open source governance
* Experimenting with rough-consensus

Personally I would like to split the talk into 3 sections

1. Motivation, Philosophy, History
2. Architecture, Technical Challenges, Lessons Learned
3. OSS governance and building a team

I am not by any means an expert rust programmer, but I have been maintaining
JavaScript runtimes (Node.js) for over 5 years. I have also worked across a number
of large scale OSS projects + Standards organizations. I'd love to talk about what
it is like coming to Rust with 0 experience, what was hard and what was empowering.

While this may not be the most deeply technical talk I do hope that I can bring
interesting and useful information to the audience about maintaining sustainable
open source projects and hopefully inspire some other JavaScript developers to
try rust out, because it is extremely powerful (and fun!).

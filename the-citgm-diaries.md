# The CITGM Diaries

## Abstract

The Canary in the Gold Mine is a smoke testing utility that automates running
unit tests of various various modules in the Node.js ecosystem, it must pass for
all controversial changes and releases. CITGM has been incredibly successful,
finding all sorts of regressions across the ecosystem and in node core itself.

I have kept a diary of all the weirdness, lets examine how things break!

## A bit more info

The Canary in the Gold Mine (CITGM) is a smoketesting utility used by the Node.js
project to test for ecosystem breakages. CITGM is able to download the source of a
module published to npm, install all the dependencies, and run it's test suite. When
the project is going to make a release or land a controversial change we are able to
automate the test suites of 70 of the top modules in the ecosystem to confirm we are
not causing unexpected breakages.

This talk will outline how CITGM works, how it fits within node.js CI, and some of
the interesting edge cases we have experienced. We will dig into the architecture of
the utility itself and look at how it is set up in Jenkins. We will also do 3
different case studies of major breakages that would not have been found with CITGM.

## Watch the talk

### Node Interactive 2016

[![Node Interactive 2016](https://img.youtube.com/vi/8is8iKlo8oQ/0.jpg)](https://www.youtube.com/watch?v=8is8iKlo8oQ)

### Node.js Madrid April 2017

[![Nodejs Mardrid](https://i.vimeocdn.com/video/628221460_640.webp)](https://vimeo.com/212275635)

### Nodejs Israel May 2017

[![Nodejs Israel](https://img.youtube.com/vi/0A6-d3y5kWk/0.jpg)](https://www.youtube.com/watch?v=0A6-d3y5kWk)
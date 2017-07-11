# The hilarious misadventures of being a platform downstream from your language.

## Abstract

There is a group called tc39, they work on a standard called ecma262. The standard is for
a language called JavaScript. This language is implemented by various vendors, generally companies who
make browsers. Google has V8, Mozilla has SpiderMonkey, Microsoft has Chakra, and
Apple has JSCore.

So there is this platform called Node.js. It has a small core philosophy and prides itself
on offering a stable ecosystem.

Here is where things get weird; What happens when new language features are specified
and they land in the VM you embed? What happens when the VM you embed updates their compiler?
What happens when you have a community that doesn't neccessarily want things to change?

### A Bit more

If you are writing JavaScript this talk covers information that is important to you. It will discuss the lifecycle of the JavaScript langauge, from standard to virtual machine to runtime. It will also discuss the type of architecture decisions project maintainers of the Node.js platform need to make in order to keep up with the pace of change happening in the specification and VM layer right now.

Understanding how the language is implemented and embedded is important to having a full grasp of what is happening when you run `npm start`.

## Watch the talk

I have not yet given this talk.

Please reach out if you are interested in seeing it at your event!

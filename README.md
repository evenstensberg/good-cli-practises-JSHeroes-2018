# Good CLI Practises

This project aims to help you creating a good CLI project by defining good defaults, creating design documents and different methods of creating a CLI tool.

## Slides

Slides for the repository can be found [here](https://github.com/ev1stensberg/good-cli-practises-JSHeroes-2018/blob/master/presentation.pdf).
## Overview 

- Introduction
- Architecture
- Performance
- Case Studies


## Introduction

This repository guides you through some design techniques mostly used in regular software engineering paradim, but some patterns could be bridged to crafting CLI tools.

The repository will also go through performance optimizations you could make, case studies with popular repositories and some useful links at the end.

## Architecture

Creating the structure of the CLI you're making is quite important. Before doing so, it is important to think about what your project should do, what the goal of the project is and what you're trying to acheive. 

It might be a good idea to write design documents, implementation details, flowcharts and similar techniques in order to get an overview of what you're creating. This way, it might be easier to figure out which design pattern works the best for you.


### Iterator Pattern
The iterator pattern is a simple pattern that sounds like what it is. You start with an iterator, which is a description of an object which will iterate through something. An iterator will need something to iterate over, and this is exactly what the iterator pattern is about. One iterates through a list or some collection of values, and make modifications to each of the values. 

You might have heard of functions like `.map`, `.reduce`, `.forEach` and similar functions. All those functions expect iterable callee's. 

For instance, if your CLI tool is fetching all your files in the directory into an array, and you want to write a different value to each of those paths, then an iterator pattern might be useful for your case. By iterating through the array items ( iterables ), you can modify each of the elements exactly how you want.


### Factorial Pattern

tbd
### State Pattern
tbd
### Generator Pattern
tbd
### Coroutines Pattern
tbd
### Decorator Pattern
tbd
### Observer Pattern
tbd
### Singleton Pattern
tbd
### Template Pattern
tbd
### Adapter Pattern
tbd
### Facade Pattern
tbd
### Flyweight Pattern
tbd
### Command Pattern
tbd
### Abstract Factory Pattern
tbd
### Composite Pattern
tbd
## Performance
tbd
## Case Studies
tbd
## Useful Links

- [Which Pipe should I use?](https://www.jstorimer.com/blogs/workingwithcode/7766119-when-to-use-stderr-instead-of-stdout)
- [Useful Modules](https://hackernoon.com/javascipt-modules-worth-using-9aa7301e41ac?gi=6406ade6a10f)
- [Linting Commits](https://github.com/marionebl/commitlint)
- [Generate a codemod based on your Source](https://github.com/noahsug/gen-codemod)
- [Cost of Small Modules](https://github.com/nolanlawson/cost-of-small-modules)
- [Open Source Guide](https://github.com/github/opensource.guide)
- [Bundlesize](https://github.com/siddharthkp/bundlesize)
- [Strip Ansi](https://github.com/chalk/strip-ansi)
- [Mock Stdin](https://github.com/caitp/node-mock-stdin)
- [Lint Staged](https://github.com/okonet/lint-staged)
- [Module Best Practises](https://github.com/mattdesl/module-best-practices)
- [V8 Compile Cache](https://github.com/zertosh/v8-compile-cache)
- [NodeFS Extra](https://github.com/jprichardson/node-fs-extra)
- [Ncp](https://github.com/AvianFlu/ncp)
- [Find up](https://github.com/sindresorhus/find-up)
- [Inquirer](https://github.com/SBoudrias/Inquirer.js)
- [Vorpal](https://github.com/dthree/vorpal)
- [ANSI 256 Colors](https://github.com/jbnicolai/ansi-256-colors)
- [Commander](https://github.com/tj/commander.js)
- [Debug](https://github.com/visionmedia/debug)
- [Clui](https://github.com/nathanpeck/clui)


### Example Repositories
- [Babel Upgrade](https://github.com/babel/babel-upgrade)
- [Pwmetrics](https://github.com/paulirish/pwmetrics)
- [Sfo](https://github.com/btholt/sfo)
- [c8](https://github.com/bcoe/c8)
- [Mac CLI](https://github.com/guarinogabriel/Mac-CLI)
- [NodeJS CLI](https://github.com/nodejs/node-core-utils)

### Misc

- [Draftlog](https://github.com/ivanseidel/node-draftlog)
- [Gifi](https://github.com/vadimdemedes/gifi)
- [Ora](https://github.com/sindresorhus/ora)
- [Time Require](https://github.com/Jaguard/time-require)




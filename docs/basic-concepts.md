# Introduction to React for the Novice Developer

## Introduction

React is a declarative front-end library. It is the `V` in your typical `MVC` software design pattern.

React is:
1. Declarative (describe **what**, **not** **how** you want to do something)
2. Component-Based (atomic design, separation of concerns)

This doesn't sound like much, but these constraints encourage developers to think in components rather than in monolithic structures leading to more maintainable, testable code-bases.

## Why would you use React?

It's hip, but that's not the best reason to give.

If you've ever built a moderately big interactive web application with all bells and whistles attached you wouldn't be asking.

Let's go through the reasons anyway:
1. State management is hard
   Your typical app keeps track of a lot of variables and your UI must _react_ to these changes (see what I did there?). State management code can get pretty messy
2. React provides a conceptual framework to reason about your app
   React has been built by developers who ran into all well-known problems that software developers of all traits run into (spaghetti, non-testable code, not extensible and much more that I can't mention without wanting to throw up ...). They extracted common problems and created frameworks to think about them in a manageable way. Elaboration below.
3. Great ecosystem
   Since React is a JavaScript-based framework, you get all the perks (and liabilities) of the NPM-ecosystem. Since React is pretty popular, people create cooler wrappers around existing JavaScript packages. You can plug-and-play virtually anything.
   Some great packages to checkout:
   - a
   - b
   - c
   - d
  
## Mapping (Classic Applications <---> React)


Classic | React | Description
---------|----------|---------
 Object (OOP) | Component | Compound entity binding logic into self-contained unit. Usually contains methods and variables 
 object variables | props | fields of the object/variables belonging to the object
  |  | 
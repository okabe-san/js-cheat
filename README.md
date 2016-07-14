# JavaScript Cheatsheet

Last updated 07/14/2016

## Primitives

Primitives are the JavaScript building blocks.

- **Number**: Floating-point and integers
  - Also: Infinity, -Infinity, and NaN
- **Boolean**: `True` or `False`
- **String**: Represents textual data
- **Undefined**: Represents a value that hasn't been defined
- **Null**: Intentional absence of an object value
- **Symbol** (new in ES6)

## Variables

Variables are containers to store data (values).
They are shortcuts for storing data.

- Declared using `var`
- Naming: should be descriptive, should use CamelCase, can't start with number, can't have spaces, avoid symbols except `_`, `$`, `-`

## Data Structures

- **Arrays**: ordered container for primitives (and other data structures), accessed via index
- **Objects**: unordered key/value pairs accessed via bracket or dot notation

## Programming Paradigms

- **Procedural**: JavaScript renders commands in order
- **Functional**: break apart code or problem logically, generally separate state from behavior; is reusable

## Flow Control

- **Flow Control**: Decides what runs based on specific conditions or loops
- **Conditionals**: Control the flow of the program
  - if, if-else, if- else
  - can be nested

## Loops and Iterations

- Allows piece of code to run for certain number of iterations
- Infinite loops run forever
- for, while, for in, for of, do while

## Operators

- **Math**: `+`, `-`, `*`, `/`, `%`, can combine (`++`, `-=`, etc.)
- **Logical**: `&&` (and), `||` (or)
- **Comparison**: `===` (strict), `==` (loose), `>`, `<`, `!`, `>=`, `<=`

## Functions

Set of instructions that achieve a specific task defined by code. Can be defined and invoked to return some output, can contain parameters (when defined) and arguments (pass in when called/invoked).

- Method: a function that is contained within an object
- Function: first class citizen and can be used as arguments in JavaScript.
  - Always returns something; if not explicitly set, then it returns `undefined`

## Variable Scope

The range in which a variable cab be accessed.
- **Global**: accessable everywhere
- **Local** (a.k.a. functional/lexical): accessable only when the function is invoked

## Hoisting

The process by which the computer moves all variable declarations to the top of the applicable scope, so that it never encounters a variable it is unaware of. It's important to note that it does not move the variable assignment to the top of the page.

_Example_:

`var foo = bar`

Hoisting moves declaration (`var foo`) but NOT assignment (`bar`)

## Higher Order Functions

Functions can take functions! The function that's passed into the HOF is a callback.

## String Concatenation

Used to join two or more strings.

'test' + 'ing'
'test'.concat('ing') //=> 'testing'

## Computer Science
- ***Big-O***: how developers discuss the complexity of an algorithm as a way to understand how fast a program will run given it's input. Big-O notation deals with the worst case scenario for the algorithm.

_Notation_:
- ***O(n)*** = Linear time (direct relationship with input size)
- ***O(1)***: Constant time (runtime remains constant regardless of input size)
- ***O(n<sup>2</sup>)***: Quadric time (runtime exponentially grows based on input size)

Link: [Big O Cheatsheet](http://bigocheatsheet.com/)

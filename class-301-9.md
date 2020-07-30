# Read: 09 - Refactoring
## What is functional programming
- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

## pure functions
- It returns the same result if given the same arguments
- It does not cause any observable side effects

## reading files function 
- not a pure function
## random number genorators
- not a pure function 

## pure function benefits
- The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts

## Immutablitity
- unchanging over time or unable to be changed
- When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

## referential transparency
- Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
- pure functions + immutable data = referential transparency

## functions as first-class entities
- The idea of functions as first-class entities is that functions are also treated as values and used as data.
- first-class function entities can:
  - refer to it from constants and variables
  - pass it as a parameter to other functions
  - return it as result from other functions

## higher-order functions
- takes one or more functions as arguments, or returns a function as its result
# Reading: Problem Domain, objects, the DOM

## Problem domain
Coding is not the most difficult part of writing an application. Figuring out the problem domain is the hardest part due to needing all the information possible about the problem at hand. Without understanding the problem domain you can not write successful and useful code. Figuring out the problem domain with help give all the answers to every question you application should answer.

## Objects
Objects take variable and functions ans groupe them together and create something you would recognize in the real world.
- Variable become properties
- functions become methods, methods represent tasks that are associated with objects

In a object properties and methods have names and values called a key, and object can not have to keys with he same name

The value of a property can be a string, number, boolean, array, or another object.

## Document Object Model (DOM)
 a dom is a separate program from html and javascript that lays out a webpage in a tree type layout to allow javascript to interact with text and other things in the html document.

 ## parts of a DOM tree
 - the document node
 - element nodes 
 - attribute nodes 
 - text nodes

 ## Working with the DOM
 1. access elements 
 2. work with elements

 ## returning single elements 
 ```getElementById('id')```
 ```querySelector('css selector')```
 ## retuning more than one element
 ```getElementsByClassName('class')```
 ```getElementsByTagName('tag name')```
 ```querySelectorAll('css selector')```
 ## adding elements 
 ```createElement()``` - create the element 
 ```createTextNode()``` - give it content 
 ```appendChild``` - add it to the DOM
 ## removing elements 
 ```removeChild```

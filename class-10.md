# Error handing and debugging
a big help when finding an error is code is knowing the steps in how the code is being executed
## Error objects in javascript
1. Syntax error 
- syntax in the code is not correct
2. Reference error
- variable not declared or out of scope 
3. Type error
- trying to use a object or method that dose not exist 
4. Range error
- using numbers outside of a functions accepted range 
5. Eval error
- run text as code through the interpreter
6. URI error 
- if /, &, #, :, ; are used in a URI
7. NaN
- if you use a mathematical operation that uses anything other than a number
## Debugging workflow 
1. Where is the problem
2. What exactly is the problem 
- browser dev tool and javascript consol are good tools to use when trying to find errors in a program. Using the consol you are abel to help tell what part of a code is working and what needs to be fixed using proses of elimination.
## methods to use when writing to the consol log 
``` console.info() ```
``` console.warn() ```
``` console.error() ```
``` console.group() ``` - if you need to write a groupe of console logs
breakingpoints help you step through your code one line at a time and see the data being out to use to identify where a problem is occurring. You can set breaking points with conditions so the code breaks when the condition is met.

You are abel to throw your own error messages to help locate and take care of one problem at a time if you know the code is going to cause a problem down the script. It is useful so you can fix a problem early instead of letting a little problem go by that affects the program later on down the script.

## Debugging tips
- try another browser if your code is having a problem, the problem could be due to the certain browser
- strip the code down to the bare minimum to try to better locate the problem 
- try explaining the code to someone else, this sometimes helps the programmer to figure it out
- search the web for help
- validation tools can help with error in code 
- go back to the basics and look for little syntax error, missed or extra characters, or data type issues

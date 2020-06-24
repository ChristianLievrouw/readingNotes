# Forms 
## different kinds of forms 
- adding text
- making choices
- submitting forms
## Form structure
``` <form action="http://www.example.com" method="get"> ```
- start with form tag
- action attribute with a page linked that will hold the information added to the form
- method will either get or post
  - get should be used for short forms such as search engine 
  - push should be used when taking in more information of user is uploading a file
# lists, tables, and forms
## Styling list
1. unordered list can be styled with
- none, disk, circle, square
2. ordered list can be styled with
- numbers, decimals, lower-case, upper-case, lower and upper roman
3. list style images
- uss css to make ul points a image 
## Styling tables
1. show, hide, inherit
- giving styling to empty cells
2. gaps between cells
- border spacing, border collapse 
## Styling forms
1. style submit button 
- use an image for the submit button, change look when hovered or clicked
2. style fieldsets, legends
- style them with width, color, background-color, borders
3. cursor styles
- set a curser to do different things when the user interacts with parts of the page
# Events
Traditional DOM event handlers
``` element.onevent = functionName; ```
Event listeners
``` element.addEventListener('event', functionName [, Boolean]); ```
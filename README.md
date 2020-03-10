## Code 201 Reading Notes

This website is going to containe my notes from class readings from the _John Duckett HTML & CSS as well as JavaScript & jQuery_ for code 201.

### 1.

### 2.

### 3. HTML lists, CSS boxes, JS controlflow
  - ordered lists are numbered, ex. instructions on how to build something
  - unordered lists are lists started with a bullet or symbol but have no order to be followed, ex. grocery list
  - defined lists are lists made up of a set of terms followed up by the definitions of those terms
  - you can nest (put inside) lists within other lists 
  - by default css boxes are sized just big enough to hold its content, but that can be manipulated
  - most popular way to manipulate boxes is to adjust them using pixels, percentages, or ems
  - when you use percenatges the size of the box is relative to the browser or relative the the box it is incased in
  - when using ems the size of the box is based on the size of the text within it 
  - you cant use percentages to control border width
  - to center content you can set the left and right margins to auto
  - if else statements let you set two codes one for true and one for fales
  - switch statements have a switch value and a case and in the case there is code that will run if the variable matched the value
  - if you use a data tyoe js did not expect it will try to make sense of the operation instead of sending an error
  - falsy ex.
      -var highscore = false;
      -var highschore = 0;
      -var highschore = ' '
      -var highschore = 10/'score
      -var highschore;
  - truthy ex. 
       -var highschore = true;
       -var highschore = 1;
       -var highschore = 'carrot';
       -var highschore = 10/5;
       -var highschore = 'true';
       -var highschore = '0';
       -var highschore = 'fales';
       
### 4. HTML links, CSS layout, JS functions
  - links let you move from one web page to another
  - all link tags are created using <a></a> tags and have an href attributw
  - there are 2 types of urls used in link tags 
    -absolute urls
      - the full website url
      - has domaine name included
      - used when linking to another website
    -relative urls
      - only part of the full url
      - does not have the domaine name
      - used when the linked pages are in the same folder
  - on larger websites its good to have each different page in a new folder (aka a directory)
  - you can use id attributes to target specific things in the page to be linked
  - css treats each html element as if it is in its own box the can be either block level or inline
  - you can control the layout of the page using positioning schemes; normal flow, relative positioning, and absolute positioning
  - you may also need to use box offset properties
  - when you use postitioning schemes boxs may over lap, elements that appear later in the html sit on top
  - you can usse the z index propety to control which is on top, the higher the numberthe closer the element is to the front
  - since screen sizes and resolutions vary so mmuch desginers try to create pages around 960 to 1000 pixels wide
  - ixed width layouts do not change the size as the user increases or decreases the size of the browser window
  - liquid layouts stretch and contract as the user increases or decreasses the browser size
  - functions consist of a seris of statements that have been grouped together because the preform and certain task
  - browser come with a set of built in objects 
  
  ### 4. 
  - images should be relevent, conay info, be recognizable, fit the color pallet
  - you should keep images in a seperate folder
  - use img tag
  - src tells browser where to find the image
  - alt provides text description of img
  -use title attribute to give more info about image
  - you can set eh height and width of an image
  - images should be placed, before a pp, in the start of a pp, or in the midlle of a pp
  - align is used to indicate how other parts of the page should flow around an image
  - you can specify color the color of text in css
  - you can specify the color in 3 ways
    - rgb values
    -hex codes
    - color names
  - every color on a computer screen is created by mixing red, green, and blue
  - when pciking foreground and background color it is important to be sure there is enough contrast to make sure text is visable
  - rgba lets you pick colors like the rgb value would but also lets you set opacity
  - hs1 lets you specify colors using hue, saturation, and lightness
  
  ### 5.
  
  ### 6.
  
  ### 7. HTML tables, JS constructor functions
  - represents info in a grid format
  - grids allow us to understand data by referancing info on two axis
  - each block ina grid is refered to as a cell
  - <table> element is used to create a table
  - heading sits inside <thead>
  - body sits in <tbody>
  - footer sitsin in <tfoot>
  - object cinstructors can use a function as a template
  - you create instances of the object using the cinstructor function
  - you can add new properties and an object
  - keyword is commonly used inside functions and objects
  - data is represented using value/pairs
  - if you want to access items via a propety name or key use an object
  - arrays are a special type of object
  - you can combine arrays and objects to create complex data structures
  - the math object has properties and methods for mathimatical constants and functions
  - in order to work with dates you create an instance of the date object
 
  
  
### **Table of Contents** 
1. Introdcutory
2. HTML Text, CSS intro, and JavaScript instructions
3. HTML lists, CSS boxes, JS controlflow
4. HTML links, CSS layout, JS functions
5. HTML images, CSS color and text 
6. JS object literals; The DOM
7. HTML tables, JS constructor functions
8. More CSS layout
9. Forms and events
10. JS debugging
11. Assorted Topics
12. Docs for the HTML <canvas> elemnt&chart.js
13. Local Storage
14. CSS transforms, transitions, and animations
15. What Google learned about teams

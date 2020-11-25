# Project Name
> Piano Keys  

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Code Examples](#code-examples)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
Piano Keys project using DOM manipulation

## Screenshots
![Example screenshot](https://github.com/TarrMarr/pianoKeys/blob/main/screenshot.JPG)

## Technologies
* HTML5
* CSS
* JavaScript

## Code Examples
Show examples of usage:
`let keyPlay = function(event){
    event.target.style.backgroundColor = 'pink';
};

let keyReturn = function(event){
    event.target.style.backgroundColor = '';
};

// Write a named function with event handler properties 
function keyColor(note){
    note.onmousedown = keyPlay;
    note.onmouseup = keyReturn;
};

// Write a loop that runs the array elements through the function
notes.forEach (function(note){
    return keyColor(note)
});

// These variables store the buttons that progress the user through the lyrics
let nextOne = document.getElementById('first-next-line');
let nextTwo = document.getElementById('second-next-line');
let nextThree = document.getElementById('third-next-line');
let startOver = document.getElementById('fourth-next-line');`


## Status
Project is:_finished_

## Inspiration
Project created for Codecademy's Full Stack Engineer 

## Contact
Created by TarrMarr(https://www.tarrynmarr.me) - feel free to contact me!

# Memory Game Project

## What is the Memory Game
The memory game is a classic remake of "concentration" in which there are 12 cards, 4 x 4 rows and columns that have randomly shuffled icons on their backside. The cards are displayed briefly and the users memory is challenged to match up previously shown cards to make a pair.

## Challenge
Match the 6 pairs of cards as quickly as possible, with as little turns as possible.

## How to Play
The game automatically begins once the user selects two cards, initializing the first pair-matching attempt. The timer will begin and the rank (in stars) will begin to decline based on the number of turns taken before completion of the game.

## Instructions
* Click on the first card
* Click on another card and attempt to retain the cards icon and location
* Continue clicking on cards, attempting to match pairs, until all pairs have been matched

## How I built the game
I combined HTML, CSS, and Javascript in order to build out the structure, styling, and functionality of the fame
* I created an interface with a grid of 12 cards, 4x4, that consists of 6 different pairs of icons in HTML
* I styled the interface with color, drop-shadows, and animations with CSS
* I created logic and the ability to track moves, rank the users performance based on moves, and keep track of game time within Javascript
* Cards have different effects and colors to represent if they are a match or not
* Upon completion of the game, a pop-up modal appears displaying the users stats (moves, time, ranking) and prompts them to play again
* I also implemented a reset button that can be utilized at any time to clear the form and reset all data
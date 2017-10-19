# 50 States Game

## Overview
In this project I implemented a game about the 50 states in the US.

The goal of the game is to input all 50 states within a time limit. If the user inputs all the states within the time limit, the user wins. If the user fails to input all the states, the user loses. Hovering over the text of state names displays the names of state senators.

## Objective
I created an HTML page with CSS elements. I also used Javascript to interact with the DOM, and AJAX to interact with APIs.

## Details:
There is an input field to enter names. The start button must be clicked to start the game, in which a timer will also start counting down to 0. Typing a state's name correctly (case-insensitive) will add it to a list of successfully named states. The list is continuously updated, so the input field is cleared for each state added, allowing the user to immediately start typing a different state's name.

When the timer ends, the user can no longer use the input field, and the results will be displayed. The user's score and a list of unsuccessfully named states then appears on the page/

If a user hovers over any state name on the screen at any point, the names of the state's senators will be shown. This is done through retrieving data from the Sunlight Foundation API through AJAX.

Documentation for the API can be found here: [Sunlight Foundation API](https://sunlightlabs.github.io/congress/legislators.html)

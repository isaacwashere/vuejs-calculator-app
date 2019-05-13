# Simple Calculator App

This is a simple, calculator app using VueJS. This app supports simple mathematical operations 


## How to Run

1. Navigate to Terminal

> open directory in your Terminal

2. Start the server:

> type "npm run serve" OR "yarn serve"

> press "enter"

3. View the app:

> open localhost:8080 in your browser (might open automatically)


## Abilities & Features

* A user can add, subtract, multiply, divide, take the percent of any positive and/or negative number 
* Each number and the answer is displayed in the calculator UI


## Notable Technologies/Functions/Methods

| Technology/Function   | Purpose                                                          |
| --------------------- |:----------------------------------------------------------------:|
| methods in the script | Check for currentNum and previousNum, and handle all operations  |

* Everything occurs in a single Calculator.vue component and it is rendered in App.vue
* All of the operations are done via methods (there are no imports to support or do anything)
* All numbers are originally strings and then parsed into floats in the "equal" method


## Future Implementation(s)

* Make the numbers stick and appear to the right, instead of the center
* When a user clicks on a number/operation/button, the view should respond accordingly 
* Make the UI nicer, maybe a background images
* Make a viewable History of operations so a user can see all the operations they make 
  - make it in real time, so they can see changes (and don't have to remember what they typed)
* Implement Testing 


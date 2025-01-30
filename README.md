# Web-Programming-4
## Program overview
This program was an introduction to for loops in javascript, this was a rather simple program as it only printed
simple numbers

## Program implementation
### HTML
- A heading is created for the page named Project 4 - Printing Numbers
- A header with the text Printing Numbers is initialized
- Two entries are initialized, they accept numbers
- Radio buttons are initialized labeled All Numbers, Odd Numbers, and Even Numbers

### JavaScript
- printResult()
  - get the two numbers from their respective entries and convert them to integers
  - get the checked status of the radio buttons
  - initialize a boolean step2 to be false
  - make a val variable
  - if the odd selection is checked, set step2 to true and set val to 0
  - if the even selection is true, set step2 to true and set val to 1
  - start a for loop for printing increasing numbers
    - if step2 is true and the number is even, continue to the next iteration
    - otherwise, write the number
  - start a for loop for printing decreasing numbers
    - if step2 is true and the number is even, continue to the next iteration
    - otherwise, write the number
 -add a button to go back to the main screen
- restart()
  - reloads the webpage            

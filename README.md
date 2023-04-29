# ascent_academy_calculator
userPressedNumber: This function is called when a number button is pressed. It appends the number to the "model" array and calls the "render" function.

addListeners: This function adds event listeners to all the buttons on the calculator.

clear: This function clears the "model" array and calls the "render" function.

isMathOperator: This function checks whether a string is a mathematical operator (+, -, *, /).

userPressedDot: This function is called when the dot (.) button is pressed. It adds a dot to the current number in the "model" array and calls the "render" function.

userPressedEqual: This function is called when the equal (=) button is pressed. It calls the "calculate" function to perform the calculation and updates the "model" array. Then, it calls the "render" function.

userPressedMathOperator: This function is called when a mathematical operator button is pressed. It appends the operator to the "model" array and calls the "calculate" function if necessary. Then, it calls the "render" function.

calculate: This function performs the arithmetic calculation based on the values in the "model" array. It updates the "model" array with the result of the calculation.

calcThree: This function performs a calculation on three values (e.g., 1 + 2). It returns the result as a string.

render: This function updates the screen with the current state of the calculator. It highlights the current operator and displays the result of the calculation in the text input field.

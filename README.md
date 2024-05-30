# Month Identifier

This project implements a Python program to determine the name of a month based on its numerical value (1-12).

## Algorithm:

1. Function Definition:

The program defines a function named MonthName that takes an integer m as input.

2. Input Validation (Implicit):

While not explicitly checking for invalid input, the conversion of user input to an integer (int(input(...))) within the main section might raise a ValueError if the user enters a non-numeric value.

3. Conditional Statements:

  -  Inside the MonthName function, a series of if-elif statements are used to handle different month number possibilities.
  -  Each if statement checks if the provided m value is equal to a specific month number (1 to 12).
  -  If a match is found, the corresponding full month name ("January", "February", etc.) is printed using the print function.

4. User Input and Function Call:

  *  In the main block of the code:
    -  An integer variable m is declared to store the user-provided month number.
    -  The program prompts the user to enter a month number between 1 and 12 using input.
    -  The user's input is converted to an integer using int and stored in the m variable.
    -  The MonthName function is called with the m value as an argument. This executes the lookup logic based on the entered number.

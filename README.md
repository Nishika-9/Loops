Algorithms:

A) Factorial-

1) Start

2) Include the necessary C++ libraries.

3) Declare a recursive function to calculate the factorial of an integer.

4) Define the main function:

a. Declare an integer variable n to store the user's input.
b. Prompt the user to enter a positive integer
c. Read the user's input into the variable n.
d. Check if the entered number is non-negative:
     If n is less than 0:
i. Display an error message: "Factorial is not defined for negative numbers."
cpp cout << "Factorial is not defined for negative numbers." << endl;
     If n is non-negative:
i. Calculate the factorial using the factorial function and display the result

5) Define the factorial function:
a. Check for the base case: If n is 0 or 1, return 1.
b. For the recursive case:

6) Calculate the factorial as n times the factorial of n-1.

7) Return the result.

8) End

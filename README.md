# Python_Guessing_Game
Task 1:
You are creating a Python program to simulate a simple guessing game. The game will have the
following rules:
1. The program will generate a random number between 1 and 50 and store it in a variable
called "secret_number." For this, you will need to import randint() from the random library in
python. Run the following line of code in a cell:
from random import randint

2. The user will be given 5 attempts to guess the "secret_number."
3. The program will use a while loop to repeatedly ask the user for their guess and provide
feedback based on their input. (Remember that input() returns a string even if the user enters
a number.)
4. First, handle the case where the user enters a non-numeric input. For this, you will need to
add a try/except block. Google the syntax and under the try block, convert the guess into an
int. If the entry is non-numeric, this conversion should fail and python will go to the except
block. Under the except block, handle this error by printing "Invalid input! Please enter a
valid number” and utilize the continue statement to allow the user to try again without
reducing their remaining attempts.
5. If the user guesses the correct number, print "Congratulations! You guessed the secret
number [secret_number] correctly!" and break out of the loop.
6. If the user's guess is too high, print "Try again! Your guess is too high. You have
[attempts_left] attempts left." where "attempts_left" is the number of remaining attempts.
7. If the user's guess is too low, print "Try again! Your guess is too low. You have [attempts_left]
attempts left."
8. If the user runs out of attempts, print "Game Over! The secret number was [secret_number].
Better luck next time!" and break out of the loop.

Task 2:
a) Write a function called num_vowels that takes in a string as an argument, and returns the
number of vowels in that string. Print out the result for the string “Learning Python is fun
and engaging.”
b) Create a function called hours_to_min that converts hours into minutes. The function should
take the number of hours as input and return the equivalent number of minutes. Test the
function with 2.5 hours and print the result.
c) Write a python function that takes in a number as an argument, and prints out the table of
that number up to 12 times that number. You may name this whatever you wish.
Sample output:
1 x 8 = 8
2 x 8 = 16
3 x 8 = 24
4 x 8 = 32
5 x 8 = 40
6 x 8 = 48
7 x 8 = 56
8 x 8 = 64
9 x 8 = 72
10 x 8 = 80
11 x 8 = 88
12 x 8 = 96
d) In your previous assignment, you wrote code that checks if a student is eligible for admission
to a university. Turn that code into a function called eligibility. The function should take two
arguments: the student's age and their previous GPA. The eligibility criteria are as follows:
- The student must be at least 18 years old.
- The student's previous GPA must be 3.0 or higher on a scale of 4.0.
The function should return True if the student meets both criteria, otherwise, return False.
Test the function with different ages and GPAs with and without keywords for example:
eligibility(30, 3.2) [will depend on which order you provided the positional arguments in the
definition]
eligibility(GPA = 2.9, age = 40)

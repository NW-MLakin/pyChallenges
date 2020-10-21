
# add.py - Add numbers together and display the result

## Concepts:
functions, argument handling, data types, loops, shell execution

## Description:
Create a script named add.py that will take numbers as arguments, add them together, and display the total.


### Base challenge:

Your script should take any amount of numbers as arguments and display the total sum of these numbers.

Your script should display custom error messages when an incorrect number of arguments have been given, or if one of the arguments is not a number.

Examples:

>python3 add.py 2 1 7 5
add.py total: 15

>python3 add.py 1
add.py error: need at least two numbers to add!

>python3 add.py 1 2 seven
add.py error: 'seven' is not a number!


### Bonus Challenge #1:

Accept floating point numbers as arguments.

>python3 add.py 1 3 4.5 7
add.py total: 15.5


### Bonus Challenge #2:

If the total is a whole number (integer), display an integer and not a float (e.g. print 5 instead of 5.0)

>python3 add.py 1.5 1.5 2
add.py total: 5


### Bonus Challenge #3 (not really Python, but still important!):

Make your script executable in the shell without using the python command.  You don't need to modify %PATH% for this.

>./add.py 2 1.5 2.5 4
add.py total: 10

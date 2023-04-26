# Assignment-1_java


Calculator
This repository contains a basic calculator program written in Java. The calculator can perform the following operations:

Addition
Subtraction
Multiplication
Division
Sum of an array
Variance of an array
Standard deviation of an array
The program is composed of three Java files:
The program is composed of three Java files, each serving a distinct purpose.
Main.java - This file is the entry point of the program and controls the overall flow of the application. It calls the appropriate methods from the other two files, UserInput.java and Calculator.java, to perform the desired calculations.

UserInput.java - This file contains functions for taking input from the user. It allows the user to enter numbers or an array of numbers, and passes this input to the Calculator.java file for processing.

Calculator.java - This file contains all of the actual calculations performed by the program. It contains methods for addition, subtraction, multiplication, division, sum of array, variance of array, and standard deviation of array. All of these methods take the user's input from UserInput.java, perform the calculations, and return the results back to Main.java.

In summary, Main.java serves as the controller, UserInput.java takes care of input, and Calculator.java performs all of the calculations.

The following methods are defined in the Calculator.java file:
add: This method takes two numbers as input and returns their sum.
subtract: This method takes two numbers as input and returns their difference.
multiply: This method takes two numbers as input and returns their product.
divide: This method takes two numbers as input and returns their quotient.
sumArray: This method takes an array of numbers as input and returns their sum.
variance: This method takes an array of numbers as input and returns its variance.
standardDeviation: This method takes an array of numbers as input and returns its standard deviation. Usage To use the calculator, simply run the Main.java file. The program will prompt you to choose an operation, and then input the necessary numbers or array. The result will be displayed on the screen.




Factorial Calculation:
This program calculates the factorial of a given number. It provides multiple input methods for user convenience such as command line arguments, scanner, buffered reader, data input stream, and console.

Input methods:
Command line args: pass the number as a command line argument when running the program.
Scanner: enter the number through the console using the Scanner class.
BufferedReader: enter the number through the console using the BufferedReader class.
DataInputStream: enter the number through the console using the DataInputStream class.
Console: enter the number through the console using the Console class (may not be available in all environments).
Once the number is entered, the program will calculate and output the factorial of the number.

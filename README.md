#  TITLE : POSITION FINDER IN NUMBER SERIES

  #  Overview:

This Python project generates a concatenated series of numbers from 1 up to a user-defined limit and identifies which number contains a digit at a specified position. It’s a simple yet interesting program for understanding string manipulation and indexing in Python.


#  Features:

1.	Accepts user input for the end number of the series (n) and digit position (pos).
2.	Constructs a continuous string of numbers from 1 to n.
3.	Efficiently determines which number’s digit corresponds to the given position.
4.	Handles out-of-range positions gracefully.
   

 #   Technologies/Tools Used:

 1.  Python 3.x: Core programming language for script execution
 2.  Standard Python libraries: No external dependencies required, making it easy to run   on any system with Python installed.
         

 #  Steps to Install & Run the Project:

1.	Ensure Python 3 is installed on your system. You can download it from python.org.
2.	Download or clone the project repository:

                     git clone <repository-url>

3.	Navigate to the project directory:

                      cd <project-directory>

4.	Run the Python script in your terminal or command prompt:

                       final-git project.py

5.	When prompted, enter the last number for the series and the digit position to find.



#  Instructions for Testing:

To test the project manually:
1.	Run the script.
2.	Input various values for n (e.g., 10, 100) and pos (valid positions within or beyond the series length).
3.	Verify the output:
a.	The series string should be correctly formed.
b.	Correct number identification for the digit at the specified position.
c.	Appropriate message when the position is out of range.
For automated testing, you could extend the project using Python's unittest framework to automate input-output assertions.



#  Sample OUTPUT :1 if digit in range 

Enter the last number to consider in the series: 15

Enter the digit position (1-based): 12

Series: 123456789101112131415

The digit at position 12 is part of number 11.

#  Sample OUTPUT :2 if digit not in ranmge 

Enter the last number to consider in the series: 15

Enter the digit position (1-based): 30

Series: 123456789101112131415

Position out of range.


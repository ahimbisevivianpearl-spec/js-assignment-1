# js-assignment-1
JavaScript and Node.js console-based student grading system for UCU Web and Mobile Application 
# Student Grading System

## Description

The Student Grading System is a simple console-based application developed using JavaScript and Node.js.

The program allows a lecturer to enter the number of students, student names, and their marks. It then calculates the appropriate grade for each student and displays the results in the console.

## Objectives

The main objective of this project is to demonstrate the use of:

- Functions
- Conditional statements
- Loops
- User input
- Meaningful output
- JavaScript comments and documentation

## Grading System

| Marks | Grade |
|-------|-------|
| 80 - 100 | A |
| 70 - 79 | B |
| 60 - 69 | C |
| 50 - 59 | D |
| Below 50 | F |

## Main Features

- Allows the user to enter multiple students.
- Accepts student names and marks.
- Calculates grades automatically.
- Displays each student's name, mark, and grade.
- Uses conditional statements to determine grades.
- Uses functions to organize the program.
- Processes students one after another.
- Provides clear output in the Node.js console.

## Functions Used

### calculateGrade()
Calculates the grade based on the student's mark.

### displayResult()
Displays the student's name, mark, and calculated grade.

### displaySummary()
Displays a completion message after all students have been processed.

### enterStudent()
Collects student information and processes each student.

## Technologies Used

- JavaScript
- Node.js
- Node.js Readline Module
- GitHub

## How to Run

1. Install Node.js on your computer.
2. Clone or download this repository.
3. Open the project folder in Visual Studio Code.
4. Open the terminal.
5. Run the following command:

```bash
node M26B13_002.js
=================================
       STUDENT GRADING SYSTEM
=================================

Enter the number of students: 3

Enter the name of student 1: Claus
Enter the mark for Claus: 90

-----------------------------
Student Name: Claus
Mark: 90
Grade: A
-----------------------------

Enter the name of student 2: Alvin
Enter the mark for Alvin: 64

-----------------------------
Student Name: Alvin
Mark: 64
Grade: C
-----------------------------

Enter the name of student 3: Joan
Enter the mark for Joan: 29

-----------------------------
Student Name: Joan
Mark: 29
Grade: F
-----------------------------

Student grading process completed.
Thank you for using the Student Grading System.

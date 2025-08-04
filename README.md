Name: Prathyush Nimmagadda
PRN: 24070123064 
Batch: ENTC A3  

# C++ Programs: Conditional Statements and Grading Logic

## Overview

This document outlines the theoretical understanding of three beginner-level C++ programs that demonstrate conditional logic. These programs focus on computing averages, determining grades, and classifying numbers based on their sign (positive, negative, or zero). They help reinforce concepts such as input handling, arithmetic operations, and control flow using if, else if, and else statements.

---

## Program 1: Grade Calculation Based on Average Marks

### Purpose
The purpose of this program is to calculate the average of marks obtained in three subjects and assign a grade based on the calculated average.

### Concepts Covered
- Input Handling: Accepts marks for three subjects using input streams.
- Arithmetic Operations: Computes the average of the marks using basic arithmetic.
- Conditional Statements: Uses a series of if-else if-else conditions to determine the corresponding grade.
- Character Data Type: Stores the final grade as a single character (e.g., 'A', 'B', 'C').

### Logic Summary
- Accept three floating-point numbers representing marks.
- Compute the average of the three marks.
- Use conditionals to determine the grade based on the average:
  - A: 90 and above
  - B: 80 to 89
  - C: 70 to 79
  - D: 60 to 69
  - F: below 60
- Display the calculated average and the assigned grade.

### Output:
Enter marks for 3 subjects: 32,65,76
Average: 10.6667%
Grade: F

yaml
Copy
Edit

---

## Program 2: Number Classification (Positive, Negative, or Zero)

### Purpose
This program identifies whether a given integer is positive, negative, or zero using conditional statements.

### Concepts Covered
- Input Handling: Accepts an integer from the user.
- Conditional Logic: Uses if-else if-else to classify the number based on its value.
- Output Message: Displays an appropriate message depending on the classification.

### Logic Summary
- Accept an integer input from the user.
- Check the sign of the number:
  - If greater than zero, it is positive.
  - If less than zero, it is negative.
  - If equal to zero, it is classified as zero.
- Display the appropriate classification result.

### Output:
Enter a number: 4
The number is positive

yaml
Copy
Edit

---

## Program 3: Repetition of Grade Calculation

### Purpose
This is a repetition of the first program and serves the same objective—to compute the average of three marks and determine the grade. It may be reused for reinforcement or additional practice.

### Output:
Enter x: 54
Enter y: 64
1st quadrant

yaml
Copy
Edit

---

## Conclusion

These programs offer a clear introduction to conditional logic in C++. They help beginners learn how to:

- Accept and process user input.
- Perform arithmetic calculations.
- Use conditional structures to make decisions.
- Display output based on logical evaluation.

Such programs are foundational in learning how real-world problems can be approached through basic contr

# CGPA Calculator

## Description
The CGPA Calculator is a simple project developed in C++ to calculate a student's grade based on their quiz, midterm, and final exam scores. This program computes the total percentage and assigns a grade based on predefined thresholds.

## Features
- Input marks for quizzes, midterm, and final exams.
- Automatic calculation of total percentage.
- Grade assignment based on percentage thresholds.
- User-friendly console-based interface.

## How It Works
1. The program prompts the user to input marks for:
   - Quiz 1 (out of 10)
   - Quiz 2 (out of 10)
   - Midterm (out of 100)
   - Final exam (out of 100)
2. It calculates the total percentage using the following weightage:
   - Quizzes: 25%
   - Midterm: 25%
   - Final exam: 50%
3. The program assigns a grade based on the calculated percentage:
   - A: 90% and above
   - B: 80% to 89%
   - C: 70% to 79%
   - D: 60% to 69%
   - E: 50% to 59%
   - Fail: Below 50%
4. The result, including the grade, is displayed to the user.


## Requirements
- A C++ compiler (e.g., GCC, Clang, or MSVC).
- Basic understanding of percentage and grade systems.

## Usage
1. Execute the program in your terminal.
2. Follow the on-screen instructions to input marks for quizzes, midterm, and final exam.
3. View the calculated percentage and grade.

## Example Input
```
Enter obtained marks of Quiz # 1 out of (10) :: 8
Enter obtained marks of Quiz # 2 out of (10) :: 9
Enter obtained marks of Mids term out of (100) :: 85
Enter obtained marks of Final term out of (100) :: 90
```

## Example Output
```
-----------------------------------------
The Obtained Grade :: A
-----------------------------------------
```

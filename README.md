# Experiment 6: Python Conditional Statements 
Aayush Vishwakarma
25070123125

## Theory

This repository contains a collection of beginner-friendly Python programs based on conditional statements. These programs demonstrate the use of `if`, `elif`, and `else` to make decisions based on user input.

Conditional statements are one of the most important building blocks in programming. They allow a program to:

* Compare values
* Make decisions
* Execute different blocks of code based on conditions

The programs included here are commonly performed as college / school lab experiments and help build a strong foundation in Python logic.


## List of Experiments

1. Check whether a number is positive, negative, or zero
2. Check whether a number is even or odd
3. Find the greatest of three numbers
4. Assign grades based on marks
5. Check whether a year is a leap year
6. Increment a given date (with validation)
7. Check whether an alphabet is a vowel or consonant
8. Calculate the gross salary of an employee
9. Calculate income tax based on annual income


## Experiment 1: Check Whether a Number Is Positive, Negative, or Zero

### Algorithm

1. Read an integer from the user
2. If the number is greater than 0, print Positive
3. Else if the number is equal to 0, print Zero
4. Else, print Negative


## Experiment 2: Check Whether a Number Is Even or Odd

### Algorithm

1. Read an integer from the user
2. Check if the number is divisible by 2
3. If divisible, print Even
4. Else, print Odd


## Experiment 3: Find the Greatest of Three Numbers

### Algorithm

1. Read three integers `a`, `b`, and `c`
2. Compare `a` with `b` and `c`
3. If `a` is greatest, print `a`
4. Else if `b` is greatest, print `b`
5. Else, print `c`


## Experiment 4: Grade Calculation Based on Marks

### Algorithm

1. Read marks obtained by the student
2. If marks ≥ 90, assign grade **A**
3. Else if marks ≥ 75, assign grade **B**
4. Else if marks ≥ 60, assign grade **C**
5. Else if marks ≥ 45, assign grade **D**
6. Else, print Fail


## Experiment 5: Check Whether a Year Is a Leap Year

### Algorithm

1. Read a year from the user
2. If the year is divisible by 4 and not divisible by 100, it is a leap year
3. Or, if the year is divisible by 400, it is a leap year
4. Otherwise, it is not a leap year


## 🔢 Experiment 6: Increment a Given Date

### Algorithm

1. Read the date in `dd/mm/yyyy` format
2. Extract day, month, and year
3. Determine the maximum number of days in the given month
4. Validate the input date
5. If the date is valid, increment the day by 1
6. Handle month-end and year-end transitions
7. Display the incremented date


## Experiment 7: Check Whether an Alphabet Is a Vowel or Consonant

### Algorithm

1. Read a character from the user
2. Check if it belongs to `a, e, i, o, u` (both uppercase and lowercase)
3. If yes, print Vowel
4. Else, print Consonant


## Experiment 8: Calculate Gross Salary of an Employee

### Algorithm

1. Read the basic salary
2. If basic salary ≤ 10,000:

   * HRA = 20%
   * DA = 80%
3. Else if basic salary ≤ 20,000:

   * HRA = 25%
   * DA = 90%
4. Else:

   * HRA = 30%
   * DA = 95%
5. Calculate gross salary = basic + HRA + DA
6. Display the gross salary


## Experiment 9: Calculate Income Tax Based on Annual Income

### Algorithm

1. Read annual income
2. If income ≤ 2,50,000 → Tax = 0
3. If income is between 2,50,001 and 5,00,000 → Tax = 5%
4. If income is between 5,00,001 and 10,00,000 → Tax = 20% (slab-wise)
5. If income > 10,00,000 → Tax = 30% (slab-wise)
6. Display the calculated tax


## Conclusion

These programs provide hands-on practice with decision-making using conditional statements in Python. By implementing these experiments, a learner gains confidence in:

* Writing logical conditions
* Handling user input
* Solving real-world problems using Python

This repository serves as a strong foundation for moving on to more advanced topics like loops, functions, and data structures.


# 2.4 Leap Year

**Objective:** Practice using conditional logic and date calculations in Python by solving problems related to leap years and the number of days in a month.

## Instructions:

You will write Python scripts to solve the problems described below. Each problem involves using conditional statements and handling user input. Test each script with different inputs to ensure your logic is correct.

### Problem 1: Determine if a Year is a Leap Year

Write a Python script that asks the user to input a year and then determines whether that year is a leap year.

#### Leap Year Rules:

A year is a leap year if it meets the following criteria:

1. The year is divisible by 4 and not divisible by 100.
2. Or, the year is also divisible by 400, in which case it **is** a leap year.

#### Requirements:

1. **Input:** 
   - Ask the user to enter a year as an integer.

2. **Processing:** 
   - Use the leap year rules to determine if the input year is a leap year.

3. **Output:**
   - Print a message indicating whether the entered year is a leap year or not.

### Problem 2: Determine the Number of Days in a Month

Write a Python script that asks the user to input a year and a month (as an integer from 1 to 12) and then calculates the number of days in that month.

#### Steps:

1. **Determine the Month:**
   - Use an `if` statement to determine the month and assign the correct number of days:
     - January, March, May, July, August, October, and December have 31 days.
     - April, June, September, and November have 30 days.
     - February has 28 days, except in a leap year when it has 29 days.

2. **Leap Year Check:**
   - For February, include a check to see if the given year is a leap year (using the rules from Problem 1). If it is a leap year, assign 29 days to February instead of 28.

#### Requirements:

1. **Input:**
   - Ask the user to enter a year and a month (1 for January, 2 for February, etc.).

2. **Processing:**
   - Use conditional statements to determine the number of days in the given month.
   - Account for leap years when the month is February.

3. **Output:**
   - Print the number of days in the specified month of the input year.

# Coursework 1st year 1st semester

**Student Information:**
- Student ID: w1954044
- Date: 28th November 2022

## Table of Contents
1. [Introduction](#introduction)
2. [Code Overview](#code-overview)
3. [User Instructions](#user-instructions)
4. [References](#references)

---

## 1. Introduction <a name="introduction"></a>

This README provides an overview of the Python code created as part of the 1st-year 1st-semester coursework. The code is designed to calculate and display academic progression outcomes based on the input of credits earned by students. The program includes both staff and student versions to accommodate different user scenarios.

## 2. Code Overview <a name="code-overview"></a>

### 2.1. Code Structure

The code is organized into two main sections: Staff Version and Student Version.

- **Staff Version:** This version allows staff members to input student data, calculate academic progression outcomes, and visualize the results through a histogram.

- **Student Version:** This version allows students to input their own data and view their academic progression outcomes.

### 2.2. Key Functions

The code includes several functions to manage input, calculation, and output:

- `credits_check(input_message)`: Ensures the validity of credit inputs.
- `histogram(progress_count, progress_mt_count, do_not_progress_count, exclude_count)`: Generates a histogram of academic outcomes.
- `main(progress_count, progress_mt_count, do_not_progress_count, exclude_count)`: Main function for staff version, handling input and calculation.
- `stuID_check()`: Validates student IDs in the student version.
- `main()`: Main function for the student version, allowing students to input their data and view outcomes.

### 2.3. Data Storage

The program stores student results in a dictionary (`stu_results`) where keys are student IDs, and values are academic outcomes. The results are displayed at the end of the student version.

### 2.4. File I/O

The code also includes functionality to write the results to a text file (`results_file.txt`) and read them back.

## 3. User Instructions <a name="user-instructions"></a>

To use this code:

1. **Staff Version:**

   - Run the code.
   - Choose option 1 for the staff version.
   - Input student data for credits earned in PASS, DEFER, and FAIL categories.
   - The code will calculate the academic progression outcome and display it.
   - Repeat for additional students or choose to exit.

2. **Student Version:**

   - Run the code.
   - Choose option 2 for the student version.
   - Input your own credits earned in PASS, DEFER, and FAIL categories.
   - The code will calculate and display your academic progression outcome.

3. **Exiting the Program:**

   - In both versions, you can choose option 3 to exit the program.

4. **Viewing Results (Part 02):**

   - After entering data in the staff version, the code will display a list of outcomes.
   - In the student version, your outcome will be displayed immediately.

5. **Viewing Results (Part 04):**

   - After using the student version, the code will display your results with student IDs.

## 4. References <a name="references"></a>

The code references Python's standard library documentation and data structures, specifically:
- Python Software Foundation [Python Standard Library](https://docs.python.org/3/library/stdtypes.html#tuples)
- Python Software Foundation [Python Runtime Services (sys)](https://docs.python.org/3/library/sys.html)
- Python Software Foundation [Data Structures](https://docs.python.org/3/tutorial/datastructures.html)

Please make sure to respect the code of conduct and use this code for educational purposes only.

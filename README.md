# Assignment

This repository contains a series of tasks designed to demonstrate various features and functionalities of spreadsheet software, such as Microsoft Excel or Google Sheets. Each task focuses on a specific aspect of data manipulation and analysis, including auto fill, flash fill, conditional formatting, logical functions, and more.

## Table of Contents

- [Task 1: Demonstrate Auto Fill and Flash Fill](#task-1-demonstrate-auto-fill-and-flash-fill)
- [Task 2: Explore Home Tab Features for Formatting](#task-2-explore-home-tab-features-for-formatting)
- [Task 3: Use Text Wrap, Merge and Center, and Number Formats](#task-3-use-text-wrap-merge-and-center-and-number-formats)
- [Task 4: Apply Conditional Formatting](#task-4-apply-conditional-formatting)
- [Task 5: Practice Sorting, Filtering, and Find & Replace](#task-5-practice-sorting-filtering-and-find--replace)
- [Task 6: Logical IF Function](#task-6-logical-if-function)
- [Task 7: Nested IF Function](#task-7-nested-if-function)
- [Task 8: AND and OR Functions](#task-8-and-and-or-functions)
- [Task 9: Built-in Functions](#task-9-built-in-functions)
- [Task 10: IF with SUMIF](#task-10-if-with-sumif)
- [Task 11: COUNTIF](#task-11-countif)
- [Task 12: AVERAGEIF](#task-12-averageif)

## Task 1: Demonstrate Auto Fill and Flash Fill

**Dataset:**

| Full Name       | First Name | Last Name | Email                       |
|-----------------|------------|-----------|-----------------------------|
| John Doe        |            |           |                             |
| Sarah Connor    |            |           |                             |
| Michael Johnson |            |           |                             |

**Steps:**
1. Use Auto Fill to create a series of dates in the first column, e.g., "01/01/2025, 01/02/2025, etc."
2. Use Flash Fill to extract the first and last names from the "Full Name" column.
3. Use Flash Fill to generate emails based on the format `<firstname.lastname@example.com>`.

## Task 2: Explore Home Tab Features for Formatting

**Dataset:**

| Product    | Quantity | Price  | Total   |
|------------|----------|--------|---------|
| Laptop     | 5        | 50000  |         |
| Smartphone | 10       | 30000  |         |
| Tablet     | 8        | 20000  |         |

**Steps:**
1. Calculate the Total as Quantity * Price using a formula.
2. Apply bold, italics, and font colors to the headers.
3. Add borders and cell shading to the table for better readability.

## Task 3: Use Text Wrap, Merge and Center, and Number Formats

**Dataset:**

| Month    | Sales    |
|----------|----------|
| January  | 1000000  |
| February | 750000   |
| March    | 1250000  |

**Steps:**
1. Enter a description below the table, e.g., "Sales performance in Q1," and apply Text Wrap to make it fit within a single cell.
2. Merge cells above the table and add the title "Quarterly Sales Report", aligning it at the center.
3. Format sales figures as currency and apply percentage formatting to show sales growth.

## Task 4: Apply Conditional Formatting

**Dataset:**

| Student Name     | Marks |
|------------------|-------|
| John Doe         | 35    |
| Sarah Connor     | 85    |
| Michael Johnson  | 60    |
| Alice Williams   | 42    |
| Peter Parker     | 20    |

**Steps:**
1. Use Conditional Formatting to highlight marks below 40 in red.
2. Apply color scales to visualize the range of marks.
3. Use data bars to show progress for each student.

## Task 5: Practice Sorting, Filtering, and Find & Replace

**Dataset:**

| Name             | Age | City      |
|------------------|-----|-----------|
| John Doe         | 25  | New York  |
| Sarah Connor     | 30  | Boston    |
| Michael Johnson  | 28  | Chicago   |
| Alice Williams   | 22  | Boston    |
| Peter Parker     | 24  | New York  |

**Steps:**
1. Sort the data by age in ascending order.
2. Apply a filter to display only the records of people from "Boston."
3. Use Find & Replace to change "New York" to "NYC."
4. Use Auto-Fit Column Width to adjust the columns for better readability.

## Task 6: Logical IF Function

**Dataset:**

| Student Name     | Marks | Result |
|------------------|-------|--------|
| John Doe         | 35    |        |
| Sarah Connor     | 85    |        |
| Michael Johnson  | 60    |        |
| Alice Williams   | 42    |        |
| Peter Parker     | 20    |        |

**Steps:**
1. Use the IF function to determine if each student passed or failed.
   - Condition: If marks are greater than or equal to 40, the result is "Pass"; otherwise, "Fail."

## Task 7: Nested IF Function

**Dataset:**

| Employee Name    | Sales  | Performance            |
|------------------|--------|------------------------|
| John Doe         | 50000  |                        |
| Sarah Connor     | 80000  |                        |
| Michael Johnson  | 30000  |                        |
| Alice Williams   | 70000  |                        |
| Peter Parker     | 90000  |                        |

**Steps:**
1. Use the Nested IF function to assign performance ratings:
   - Sales > 80000: "Excellent"
   - Sales between 50000 and 80000: "Good"
   - Sales < 50000: "Needs Improvement"

## Task 8: AND and OR Functions

**Dataset:**

| Candidate Name   | Age | Experience (Years) | Eligible |
|------------------|-----|--------------------|----------|
| John Doe         | 28  | 3                  |          |
| Sarah Connor     | 22  | 1                  |          |
| Michael Johnson  | 30  | 5                  |          |
| Alice Williams   | 26  | 2                  |          |
| Peter Parker     | 24  | 4                  |          |

**Steps:**
1. Use the AND function to check eligibility:
   - Age ≥ 25 and Experience ≥ 3 years → Eligible
2. Use the OR function to check if either condition (Age ≥ 25 OR Experience ≥ 3 years) is true.

## Task 9: Built-in Functions

**Dataset:**

| Numbers |
|---------|
| 12      |
| 45      |
| 67      |
| 23      |
| 89      |

**Steps:**
1. Use `SUM()` to calculate the total.
2. Use `MIN()` and `MAX()` to find the smallest and largest numbers.
3. Use `COUNT()` to count how many numbers exist.
4. Use `COUNTA()` to count non-empty cells.
5. Use `COUNTBLANK()` to count blank cells.
6. Use `AVERAGE()` to calculate the mean of the numbers.

## Task 10: IF with SUMIF

**Dataset:**

| Region | Sales  |
|--------|--------|
| North  | 50000  |
| South  | 30000  |
| East   | 40000  |
| North  | 60000  |
| South  | 20000  |

**Steps:**
1. Use `SUMIF()` to calculate the total sales for the "North" region.
2. Use `IF()` to check if the total sales for "North" exceed 100000. If true, display "Target Achieved"; otherwise, "Target Not Achieved."

## Task 11: COUNTIF

**Dataset:**

| Product    | Quantity |
|------------|----------|
| Laptop     | 10       |
| Smartphone | 5        |
| Tablet     | 8        |
| Laptop     | 15       |
| Smartphone | 20       |

**Steps:**
1. Use `COUNTIF()` to count how many times "Laptop" appears in the dataset.
2. Use `COUNTIF()` to count products with a quantity greater than 10.

## Task 12: AVERAGEIF

**Dataset:**

| Department | Salary |
|------------|--------|
| HR         | 30000  |
| IT         | 50000  |
| HR         | 35000  |
| IT         | 60000  |
| HR         | 40000  |

**Steps:**
1. Use `AVERAGEIF()` to calculate the average salary for the "HR" department.
2. Use AVERAGEIF() to calculate the average salary for the "IT" department.


## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on the code of conduct, and the process for submitting pull requests.

## Acknowledgments

- Thanks to all the contributors who participated in this project.
- Special thanks to [Your Name] for the guidance and support.


# Employee Department Report

## Overview

This project is a Python automation script designed to read employee data from a CSV file, process it to count the number of employees in each department, and write a summary report to a text file. The script uses the CSV module to handle and analyze the data.

## File Structure

- `employee_script.py`: The main Python script that performs the data processing and report generation.
- `employees.csv`: A CSV file containing employee data with fields including "Department".
- `report3.txt`: The output text file that will contain the department counts.

## CSV File Format

The `employees.csv` file should have the following format:

## Script Functionality

1. **Read Employees**: 
   - The script reads the `employees.csv` file using a custom CSV dialect (`empDialect`).
   - Each row is stored as a dictionary in a list.

2. **Process Data**:
   - Extracts the department names from the employee data.
   - Counts the number of employees in each department.
   - Stores the results in a dictionary where the keys are department names and the values are counts.

3. **Write Report**:
   - Writes the department counts to `report3.txt`.
   - The output format is `DepartmentName:Count`, sorted by department name.

## Getting Started

1. **Setup**:
   - Ensure you have Python 3 installed on your machine.
   - Place `employees.csv` in the same directory as the script.

2. **Run the Script**:
   - Execute the script using the command:
     ```bash
     python employee_script.py
     ```

3. **Check Results**:
   - After running the script, check `report3.txt` for the department counts.

## Example

Given an `employees.csv` file with the following data:




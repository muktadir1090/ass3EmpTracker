# ass3EmpTracker

This project is a simple Employee Tracker application that allows users to collect and manage employee data. The application provides functionalities to add employees, calculate the average salary, display a random employee, and list all employees in a sorted order by last name in an HTML table.

## Features

- **Add Employees:** Collect employee data through prompts and store it in an array of employee objects.
- **Calculate Average Salary:** Compute and display the average salary of all the employees.
- **Select a Random Employee:** Randomly select and display an employee from the list.
- **Display Employees:** List all employees in a table, sorted by last name, with salaries formatted as currency.

## Project Structure

### JavaScript Functions

1. **collectEmployees:** 
   - Prompts the user to input employee data (first name, last name, and salary).
   - Adds each employee to an array of employee objects.
   - Validates user input to ensure correct data types.

2. **displayAverageSalary:**
   - Takes an array of employee objects as input.
   - Calculates the average salary.
   - Displays the average salary in the console, formatted as USD currency.

3. **getRandomEmployee:**
   - Randomly selects an employee from the employee array.
   - Displays the selected employee's first and last name in the console.

4. **displayEmployees:**
   - Displays the employee data in an HTML table.
   - Sorts the employees by last name before displaying.
   - Formats salary as currency.

5. **trackEmployeeData:**
   - Orchestrates the workflow: collects employees, calculates and displays the average salary, selects and displays a random employee, sorts the employees, and finally displays them in the table.

### Event Listener

- **addEmployeesBtn:** The button with the ID `add-employees-btn` triggers the employee data collection and displays the results when clicked.

## How to Run

1. Ensure you have an HTML file that includes this JavaScript file and contains an element with the ID `employee-table` where the employee data will be displayed, and a button with the ID `add-employees-btn` to trigger the employee tracking process.

2. Load the HTML file in a web browser.

3. Click the "Add Employees" button to start entering employee data.

# Employee Payroll Tracker

## Description

The Employee Payroll Tracker is a web application designed for payroll managers to efficiently manage and view employee payroll data. This application runs in the browser, featuring a dynamic and responsive user interface powered by JavaScript. It allows users to input employee information, view the data sorted alphabetically, and access computed payroll statistics.

## Features

- Add multiple employees with their first name, last name, and salary
- Display employee data sorted alphabetically by last name
- Calculate and display average salary across all employees
- Randomly select and display an employee's information
- Responsive design that adapts to various screen sizes

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Installation

No installation is required. To use the application:

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser.

## Usage

1. Click the "Add Employees" button to start adding employee data.
2. Enter the first name, last name, and salary for each employee when prompted.
3. Choose to continue adding employees or finish data entry.
4. View the sorted employee data displayed on the page.
5. Check the console for additional computed data (average salary and random employee selection).

## Implementation Details

The following key functions were implemented to meet the project requirements:

1. `collectEmployees()`: 
   - Allows users to add multiple employees
   - Prompts for first name, last name, and salary
   - Validates salary input (defaults to $0 if invalid)
   - Returns an array of employee objects

2. `displayAverageSalary(employeesArray)`:
   - Calculates and displays the average salary of all employees
   - Logs the result to the console

3. `getRandomEmployee(employeesArray)`:
   - Randomly selects an employee from the array
   - Logs the selected employee's full name to the console

These functions work in conjunction with the provided `displayEmployees()` and `trackEmployeeData()` functions to create a fully functional payroll tracking system.

## Installation

No installation is required. To view the portfolio:

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser.

Alternatively, visit the live site at [turriettaa.github.io/Employee-Payroll-Tracker](https://turriettaa.github.io/Employee-Payroll-Tracker).
## Screenshot

<img src="Screenshot 2024-09-13 131350.png" alt="Site Screenshot">

## Contributing

This project is part of a coding bootcamp assignment and is not open for contributions. However, feedback and suggestions are welcome.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- This project was completed as part of the [UC Berkeley Coding Bootcamp] curriculum.
- Starter code was provided by the bootcamp, with key functionalities implemented by [Alejandro Turrietta].
- Assisted with Amazon Q

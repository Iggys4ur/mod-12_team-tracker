
# [Module 12] Team Tracker: SQL-Based Employee Management System

## Overview

Team Tracker is a command-line application designed to manage a company's employee database efficiently. Built using Node.js, Inquirer, and MySQL, this application serves as a Content Management System (CMS) for non-developers to interact with the company's data. Team Tracker allows users to view, add, and manage departments, roles, and employees within a company, providing a structured way to keep track of employee information.

## Features

- **View Employee Data**: Easily view a list of all employees, their roles, and departments.
- **Add Employee Information**: Add new employees, roles, and departments to the database.
- **Update Employee Roles**: Change an employee's role to reflect their current position.
- **View Department and Role Data**: Access information on different departments and roles within the company.

## Technologies Used

- **Node.js**: For building the command-line interface and handling server-side operations.
- **Inquirer.js**: To create an interactive command-line experience and capture user input.
- **MySQL**: A relational database management system to store and manage company data.
- **SQL**: Used to query and manipulate the relational database.

## Installation

To install and run Team Tracker locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd team-tracker
   ```
3. Install the necessary dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the application using Node.js:
   ```bash
   node index.js
   ```
2. Follow the prompts provided by Inquirer to interact with the employee database. You can:
   - View all employees
   - Add a new employee
   - Update an employee's role
   - View all departments
   - View all roles

## Database Schema

The database schema includes the following tables:

- **Departments**: Stores department names and ids.
- **Roles**: Stores job titles, role ids, department ids, and salary information.
- **Employees**: Stores employee ids, first and last names, job titles, departments, salaries, and manager information.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to the developers of Node.js, Inquirer.js, and MySQL for providing the tools that made building this application possible.
- Special thanks to all contributors who provided feedback and support during the development of Team Tracker.

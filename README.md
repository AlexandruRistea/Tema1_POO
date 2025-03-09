# Tema1_POO
# Company Management System

This project is a simple company management system implemented in C++. It models a company structure with employees, departments, and the company itself using object-oriented programming (OOP) concepts such as encapsulation, constructors, destructors, operator overloading, and dynamic memory management.

## Features

- **Classes and Objects:**
  - `Persoana` (Person): Represents an employee with attributes like age, name, surname, and salary.
  - `Departament` (Department): Contains a list of employees and tracks the number of employees.
  - `Companie` (Company): Manages multiple departments and tracks their count.
- **OOP Concepts Used:**
  - Constructors: Default, parameterized, copy constructor.
  - Destructor: Cleans up resources.
  - Operator Overloading: `operator=`, `operator<<` for output stream.
  - Encapsulation: Getters and setters for data members.
  - Dynamic Memory Management: Vectors are used to manage employees and departments dynamically.
- **Adding Employees and Departments:**
  - Employees can be added to departments.
  - Departments can be added to a company.

## How It Works

1. **Create Employees:** Instantiate `Persoana` objects with name, surname, age, and salary.
2. **Create Departments:** Add employees to a `Departament` object.
3. **Create a Company:** Add departments to a `Companie` object.
4. **Display Data:** Use overloaded `operator<<` to print company details.

## Installation & Usage

1. Compile the program:
   ```sh
   g++ -o company main.cpp -std=c++11
   ```
2. Run the program:
   ```sh
   ./company
   ```

## Future Improvements

- Implement file-based storage to save and load employee data.
- Add an interactive menu for user input.
- Introduce more detailed employee attributes like position and work hours.

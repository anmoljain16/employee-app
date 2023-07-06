# Employee Management Web Application

This is a web application built using Node.js, Express.js, and MongoDB for managing employee data. The application provides various functionalities to retrieve, add, update, and delete employee records.

## Features

- Retrieve all employees
- Retrieve an employee by ID
- Add a new employee
- Update an existing employee
- Delete an employee

## Technologies Used

- Node.js
- Express.js
- MongoDB

## Prerequisites

Before running the application, ensure that you have the following installed:

- Node.js
- MongoDB 

## Getting Started

1. Clone the repository:

```
git clone https://github.com/anmoljain16/employee-app.git
```
```
cd employee-app
npm install
```
```
npm start
```

The application will be running at `http://localhost:3000`.

## API Endpoints

- **GET /api/employees**: Retrieve a list of all employees.
- **GET /api/employee/:id**: Retrieve an employee by their ID.
- **POST /api/employee**: Add a new employee.
- **PUT /api/employee/:id**: Update an existing employee by their ID.
- **DELETE /api/employee/:id**: Delete an employee by their ID.

## Error Handling

The application handles error scenarios and provides meaningful error messages in case of failures or invalid user input.





# Full Stack Employee Management

A full-stack employee management application built with React, Spring Boot, and MySQL.

## Technologies

- React
- Java
- Spring Boot
- MySQL
- REST API

## Features

- Add employees
- View employee information
- Update employee information
- Delete employees

## Project Structure

- `react-frontend` - React frontend
- `springboot-backend` - Spring Boot backend

## Run locally

Create a MySQL database named `employee_management_system` and set `DB_PASSWORD`
to the password of your local database user. Set `DB_USER` and `DB_URL` if your
database is not on `localhost:3306` or uses a user other than `root`.

Start the backend with `cd springboot-backend && ./mvnw spring-boot:run`.
In another terminal, start the frontend with
`cd react-frontend && npm ci && npm start`. The frontend expects the API at
`http://localhost:8080/api/v1/employees`.

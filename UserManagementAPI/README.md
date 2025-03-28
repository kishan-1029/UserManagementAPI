# User Management API

This is a simple .NET Core API for managing users with CRUD operations.

## Features:
- Create, Read, Update, and Delete (CRUD) users
- Middleware for request logging
- OpenAPI (Swagger) integration for easy API testing

## Installation:
1. Clone this repository
2. Open the project in Visual Studio Code
3. Run `dotnet restore` to install dependencies
4. Start the project with `dotnet run`

## API Endpoints:
- `GET /api/users` → Get all users
- `GET /api/users/{id}` → Get user by ID
- `POST /api/users` → Create a new user
- `PUT /api/users/{id}` → Update user details
- `DELETE /api/users/{id}` → Delete a user

## Author:
- Developed using GitHub Copilot

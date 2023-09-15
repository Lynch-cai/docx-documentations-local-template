# Authentication Controllers Documentation

The `authControllers.ts` file contains controllers responsible for handling authentication-related actions in the project. This documentation provides an overview of the available controllers, their functions, and how to use them.

## Table of Contents

1. [Overview](#overview)
2. [Available Controllers](#available-controllers)
3. [Controller Functions](#controller-functions)
4. [Usage Examples](#usage-examples)

## Overview

Authentication controllers play a crucial role in managing user authentication and authorization within the application. These controllers handle tasks such as user registration, login, password reset, and more.

## Available Controllers

### `registerUser(req: Request, res: Response): void`

The `registerUser` controller is responsible for user registration. It receives a user registration request, validates the input data, and creates a new user account.

### `loginUser(req: Request, res: Response): void`

The `loginUser` controller handles user login. It verifies user credentials and issues an authentication token upon successful login.

### `resetPassword(req: Request, res: Response): void`

The `resetPassword` controller allows users to reset their passwords. It sends a password reset link to the user's email address and updates the password upon confirmation.

## Controller Functions

### `registerUser(req: Request, res: Response): void`

#### Input Parameters

-   `req` (Request): The HTTP request object containing user registration data.
-   `res` (Response): The HTTP response object for sending the registration result.

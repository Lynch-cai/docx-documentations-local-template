# Controllers Documentation

Controllers in the project play a crucial role in handling various HTTP requests, processing data, and orchestrating the application's behavior. This documentation provides an overview of the available controllers, their responsibilities, and usage examples.

## Table of Contents

1. [Overview](#overview)
2. [Authentication Controllers](#authentication-controllers)
3. [Shop Controllers](#shop-controllers)
4. [User Controllers](#user-controllers)
5. [Usage Examples](#usage-examples)

## Overview

Controllers act as intermediaries between the HTTP routes/endpoints and the underlying business logic or data models. They receive incoming requests, process them, and send back appropriate responses. In this project, we have organized controllers based on different aspects of the application, such as authentication, shop management, and user-related actions.

## Authentication Controllers

### `authControllers.ts`

Authentication controllers are responsible for managing user authentication and authorization within the application.

-   `registerUser(req: Request, res: Response): void`: Handles user registration.
-   `loginUser(req: Request, res: Response): void`: Manages user login.
-   `resetPassword(req: Request, res: Response): void`: Allows users to reset their passwords.

For detailed information about authentication controllers, refer to [authControllers.md](/documentations/authControllers.md).

## Shop Controllers

### `shopController.ts`

Shop controllers handle operations related to product management and order processing in the project.

-   `getAllProducts(req: Request, res: Response): void`: Retrieves a list of all available products.
-   `getProductById(req: Request, res: Response): void`: Fetches product details based on a given product ID.
-   `createProduct(req: Request, res: Response): void`: Allows the creation of new products in the shop's inventory.
-   `updateProduct(req: Request, res: Response): void`: Enables the modification of existing product information.
-   `deleteProduct(req: Request, res: Response): void`: Handles the removal of a product from the shop's inventory.

For detailed information about shop controllers, refer to [shopController.md](/documentations/shopController.md).

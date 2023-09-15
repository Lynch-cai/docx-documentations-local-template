# Shop Controller Documentation

The `shopController.ts` file contains controllers responsible for managing the shop-related actions and operations in the project. This documentation provides an overview of the available controllers, their functions, and how to use them.

## Table of Contents

1. [Overview](#overview)
2. [Available Controllers](#available-controllers)
3. [Controller Functions](#controller-functions)
4. [Usage Examples](#usage-examples)

## Overview

The shop controllers handle various operations related to product management, order processing, and other shop functionalities within the application.

## Available Controllers

### `getAllProducts(req: Request, res: Response): void`

The `getAllProducts` controller retrieves a list of all available products in the shop and sends them as a response.

### `getProductById(req: Request, res: Response): void`

The `getProductById` controller fetches product details based on a given product ID and sends the details as a response.

### `createProduct(req: Request, res: Response): void`

The `createProduct` controller allows for the creation of new products in the shop's inventory. It receives product details in the request body and adds the product to the database.

### `updateProduct(req: Request, res: Response): void`

The `updateProduct` controller enables the modification of existing product information. It receives updated product details in the request body and updates the corresponding product in the database.

### `deleteProduct(req: Request, res: Response): void`

The `deleteProduct` controller handles the removal of a product from the shop's inventory based on the provided product ID.

## Controller Functions

### `getAllProducts(req: Request, res: Response): void`

#### Input Parameters

-   `req` (Request): The HTTP request object for retrieving all products.
-   `res` (Response): The HTTP response object for sending the list of products.

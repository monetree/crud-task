# Backend Documentation

## Introduction

Welcome to the documentation for our Node.js backend. This guide provides an overview of the backend structure, setup, and functionalities.

## Setup

1. Clone the repository.
2. Navigate to the `backend` directory.
3. Run `npm install` to install dependencies.
4. Start the server with `npm start`.

## File Structure

- **index.js**: Main entry point of the backend application.
- **/config**: Configuration files for database and environment settings.
- **/controllers**: Controller functions for route handling and business logic.
- **/models**: Mongoose models for interacting with MongoDB.
- **/routes**: Route definitions for API endpoints.
- **/middlewares**: Custom middleware functions.
- **/utils**: Utility functions and helpers.

## MongoDB Connection

The backend connects to MongoDB for data storage. Configuration details are in `config/database.js`.

## API Endpoints

- **Authentication**: `/api/auth`
- **Users**: `/api/users`
- **Products**: `/api/products`
- **Orders**: `/api/orders`

Refer to individual route files for detailed endpoint information.

## Additional Documentation

For detailed information on specific components or functionalities, refer to README files in respective directories.

For any questions or assistance, feel free to contact us.

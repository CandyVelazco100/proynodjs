# CRUD Application Example

## Introduction
This repository contains an example CRUD (Create, Read, Update, Delete) application used in class. It is built using Node.js, Express.js, and MySQL, demonstrating the basics of building a full-stack application with these technologies.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Database Setup](#database-setup)
- [API Endpoints](#api-endpoints)
- [Contributors](#contributors)
- [License](#license)

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/CandyVelazco100/proynodjs.git
    ```
2. Navigate to the project directory:
    ```sh
    cd proynodjs
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage
1. Ensure MySQL server is running and the database is properly configured (see [Database Setup](#database-setup)).
2. Start the application:
    ```sh
    npm start
    ```
3. The application will be running on `http://localhost:3000`.

## Features
- Basic CRUD operations for managing data.
- Built with Node.js and Express.js for server-side logic.
- MySQL database for data storage.
- Handlebars used for templating.

## Dependencies
- Node.js
- Express.js
- MySQL
- Handlebars

## Configuration
1. Create a `.env` file in the root directory.
2. Add the following environment variables:
    ```env
    DB_HOST=your_database_host
    DB_USER=your_database_user
    DB_PASSWORD=your_database_password
    DB_NAME=your_database_name
    ```

## Database Setup
1. Create a MySQL database.
2. Import the database schema from `src/database/schema.sql`.

## API Endpoints
- `GET /` - Retrieve all records.
- `POST /create` - Create a new record.
- `PUT /update/:id` - Update an existing record.
- `DELETE /delete/:id` - Delete a record.

## Contributors
- Candy Velazco ([CandyVelazco100](https://github.com/CandyVelazco100))

## License
This project is licensed under the MIT License.

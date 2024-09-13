# E-Commerce Back End (ORM Challenge)

## Description

This project focuses on building the back end for an e-commerce website, leveraging the latest technologies like **Express.js** and **Sequelize** to interact with a **PostgreSQL** database. E-commerce, also known as internet retail, has become a vital part of the electronics industry, empowering businesses and consumers to buy and sell products online efficiently. 

This challenge requires creating a fully functional back end for managing categories, products, and tags with a suite of APIs.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Walkthrough Video](#walkthrough-video)
- [Technologies Used](#technologies-used)
- [License](#license)

## Installation

1. Clone the starter code repository:
2. Install the ncessary dependencis:
    npm install
3. Create a .env file in the root of your project to configure your environment variables:
    DB_NAME='your-database-name'
    DB_USER='your-postgres-username'
    DB_PASSWORD='your-postgres-password'
4. Set up the database by running the schema and seed commands:
    npm run schema
    npm run seed
5. Start the application:
    npm run start

# Usage

Once the server is running, you can test the following API routes using tools like Insomnia Core:

GET /api/categories
GET /api/products
GET /api/tags
For creating, updating, and deleting data, use the POST, PUT, and DELETE routes respectively:

POST /api/categories
POST /api/products
POST /api/tags

# User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

# Acceptance Criteria

Acceptance Criteria
Database Connection:

Add your database name, PostgreSQL username, and password to the environment variables.
The application should connect to the database using Sequelize.
Schema and Seed:

When schema and seed commands are run, a development database is created and seeded with test data.
Application Start:

The server starts successfully, syncing the Sequelize models to the PostgreSQL database.
API Routes:

Use GET routes for categories, products, and tags to retrieve data in JSON format.
API Testing:

Test POST, PUT, and DELETE routes in Insomnia Core to create, update, and delete data successfully.

# Walkthrough Video

A walkthrough video demonstrating the application's functionality can be found here.
https://drive.google.com/file/d/1rF7LnK-NAH3p5HVpdGUW5ma3E46T1rM0/view

# Technologies Used

Node.js
Express.js
Sequelize
PostgreSQL
Insomnia Core (for testing API routes)

# License

This project is licensed under the MIT License.

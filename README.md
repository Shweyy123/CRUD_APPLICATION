
 # CRUD_APPLICATION

This is a CRUD (Create, Read, Update, Delete) application built using Node.js, Express, and MongoDB. The application allows users to perform basic CRUD operations on data.

## Features

- Add new data
- Read existing data
- Update data
- Delete data

## Technologies Used

- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express**: A fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB**: A document-oriented NoSQL database used to store the application's data.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

       git clone https://github.com/Shweyy123/CRUD_APPLICATION.git
       cd CRUD_APPLICATION
   
2. Install the dependencies:

       npm install

3. Set up your MongoDB database and add the connection string to a .env file:

       MONGO_URI=your_mongodb_connection_string

4. Start the application:

       npm start


## Usage

Once the application is running, you can access it at http://localhost:3000. Use the interface to add, read, update, and delete data.

## API Endpoints

The application provides the following API endpoints:

GET /api/data: Retrieve all data.

POST /api/data: Add new data.

GET /api/data/
: Retrieve data by ID.

PUT /api/data/
: Update data by ID.

DELETE /api/data/
: Delete data by ID.




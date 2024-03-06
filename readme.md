# Book-CRUD-API-Mongoose
- A backend API for managing book data through CRUD operations using Mongoose for interacting with MongoDB
- Endpoints for adding, retrieving, updating, and deleting book records
- Retrieval of all books or specific books by ID (GET request to /book & /book/:id)
- Error handling and middleware setup for CORS policy enforcement

## Usage
- Nodejs installed
- `npm i` to install dependencies: `cors, express, mongoose, nodemon`
- MongoDB server running locally on default port 27017 (`mongod` || `brew services start mongodb/brew/mongodb-community`)
- run `npm run dev` to execute 'nodemon index.js'
- Once server is running on *localhost:5555*, access the API endpoints using *Postman*
    - View & interact with database using *MongoDB Compass* or *MongoDB Shell, mongosh*

## What is CRUD?
- Create, Read, Update, and Delete. Represents the four basic functions that can be performed on most types of data:
    - Create: Allows the creation of new data entries or records in a database.
    - Read: Involves retrieving or accessing existing data entries from a database.
    - Update: Enables modification or alteration of existing data entries in a database.
    - Delete: Involves removing or deleting existing data entries from a database.

### CRUD Operations, Postman Testing, Express Router, Middleware Setup, CORS Policy Implementation
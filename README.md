# Books REST API

## Project Title
Task 3: Create a REST API to Manage a List of Books Using Node.js and Express

---

## Objective
Build a simple REST API that performs CRUD (Create, Read, Update, Delete) operations on a list of books using Node.js and Express.  
The data is stored in memory (no database used).

---

## Tools Used
- Node.js
- Express.js
- Postman
- VS Code

---

## How to Run the Project

###  Clone the Repository
git clone <your-repository-link>

###  Navigate to Project Folder
cd books-rest-api

###  Install Dependencies
npm install

###  Start the Server
node index.js

Server will run at:
http://localhost:3000

---

## API Endpoints

### 🔹 GET /books
Returns all books.

### 🔹 POST /books
Adds a new book.

Example Request Body:
{
  "title": "The Alchemist",
  "author": "Paulo Coelho"
}

### 🔹 PUT /books/:id
Updates a book by ID.

Example:
PUT /books/1

### 🔹 DELETE /books/:id
Deletes a book by ID.

Example:
DELETE /books/1

---

## Testing
All endpoints were tested using Postman.

---

## Key Concepts Learned
- REST API fundamentals
- HTTP methods (GET, POST, PUT, DELETE)
- Express routing
- Middleware (express.json())
- JSON handling
- Status codes (200, 201, 404)

---

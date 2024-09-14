# 📞🧾Contact Manager

**Contact Manager** is a backend starter template for managing and organizing contacts using Node.js and Express. This project provides a foundational API for performing CRUD operations on contact data.

## Features

- **CRUD Operations:** Implement endpoints to create, read, update, and delete contacts.
- **Basic Data Storage:** Utilize MongoDB for storing and managing contact information.

## Tech Stack

**Server:** Node.js, Express

**Database:** MongoDB

## API Reference

**Endpoints:**

- **GET /api/contacts**  
  Retrieve all contacts.

- **POST /api/contacts**  
  Add a new contact.  
  Request Body:
  ```json
  {
    "name": "John Doe",
    "email": "john.doe@example.com",
    "phone": "123-456-7890"
  }
  ```

- **GET /api/contacts/:id**  
  Retrieve a single contact by ID.

- **PUT /api/contacts/:id**  
  Update an existing contact.  
  Request Body:
  ```json
  {
    "name": "John Doe",
    "email": "john.doe@example.com",
    "phone": "987-654-3210"
  }
  ```

- **DELETE /api/contacts/:id**  
  Delete a contact by ID.

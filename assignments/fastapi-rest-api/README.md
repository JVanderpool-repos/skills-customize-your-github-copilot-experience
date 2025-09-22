# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build and document RESTful APIs using the FastAPI framework in Python. By the end of this assignment, you will have created a simple API with endpoints for creating, reading, updating, and deleting resources.

## 📝 Tasks

### 🛠️	Set Up FastAPI Project

#### Description
Set up a new FastAPI project and run a basic server.

#### Requirements
Completed program should:
- Install FastAPI and Uvicorn
- Create a main FastAPI app file
- Run the server locally and access the default docs at `/docs`

### 🛠️	Implement CRUD Endpoints

#### Description
Add endpoints to your FastAPI app to support Create, Read, Update, and Delete (CRUD) operations for a simple resource (e.g., items, books, users).

#### Requirements
Completed program should:
- Define a Pydantic model for your resource
- Implement endpoints for:
  - Creating a new resource (POST)
  - Reading all resources (GET)
  - Reading a single resource by ID (GET)
  - Updating a resource by ID (PUT or PATCH)
  - Deleting a resource by ID (DELETE)
- Return appropriate status codes and responses

### 🛠️	(Optional) Add Extra Features

#### Description
Enhance your API with additional features.

#### Requirements
Completed program could:
- Add input validation and error handling
- Use in-memory storage (dictionary/list) or integrate with a database
- Add authentication (e.g., API key)
- Write OpenAPI documentation or add custom docs

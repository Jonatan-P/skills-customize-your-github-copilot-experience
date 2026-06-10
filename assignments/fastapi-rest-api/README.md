# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to create a RESTful API using FastAPI by defining endpoints, handling HTTP methods, and returning JSON responses.

## 📝 Tasks

### 🛠️ Set up a FastAPI application

#### Description
Create a new FastAPI app with a base route and configure it to return JSON responses.

#### Requirements
Completed program should:

- Install and import `fastapi` and `uvicorn`
- Define a FastAPI application instance
- Add a root endpoint at `/` that returns a welcome message in JSON


### 🛠️ Create CRUD endpoints for items

#### Description
Build REST endpoints to create, read, update, and delete items from an in-memory data store.

#### Requirements
Completed program should:

- Use a Python dictionary or list to store items in memory
- Implement endpoints for:
  - `GET /items/` to list all items
  - `GET /items/{item_id}` to return a single item
  - `POST /items/` to create a new item
  - `PUT /items/{item_id}` to update an existing item
  - `DELETE /items/{item_id}` to remove an item
- Return appropriate JSON responses for successful and failed operations


### 🛠️ Validate request data and handle errors

#### Description
Use FastAPI models and response status codes to validate inputs and show clear error messages.

#### Requirements
Completed program should:

- Define Pydantic models for item creation and updates
- Validate required fields such as `name` and `description`
- Return `404 Not Found` when an item does not exist
- Return `400 Bad Request` for invalid input data

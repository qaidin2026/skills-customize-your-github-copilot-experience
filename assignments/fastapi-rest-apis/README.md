# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with the FastAPI framework to practice defining routes, accepting request data, and returning structured responses. By completing this assignment, you will learn how HTTP methods map to application actions and how to test API endpoints.

## 📝 Tasks

### 🛠️ Create API Routes

#### Description
Create a FastAPI application that manages a collection of books. Define routes that allow clients to view the collection and retrieve one book by its ID.

#### Requirements
Completed program should:

- Create a FastAPI application in `main.py`.
- Store at least three books with an integer `id`, a `title`, and an `author`.
- Add a `GET /books` endpoint that returns all books.
- Add a `GET /books/{book_id}` endpoint that returns one matching book.
- Return a 404 response when the requested book ID does not exist.

### 🛠️ Add Create and Update Operations

#### Description
Extend the API so clients can add new books and update existing books using validated request data.

#### Requirements
Completed program should:

- Define a Pydantic model for the book data accepted by the API.
- Add a `POST /books` endpoint that creates and returns a new book.
- Assign a unique integer ID to each new book.
- Add a `PUT /books/{book_id}` endpoint that updates an existing book.
- Return a 404 response when a `POST` or `PUT` operation cannot find the requested resource.
- Run the FastAPI server and verify the endpoints using the interactive `/docs` page.

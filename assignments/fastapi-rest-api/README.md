# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful APIs using the FastAPI framework in Python. By completing this assignment, you will understand the basics of API endpoints, request/response handling, and data validation.

## 📝 Tasks

### 🛠️ Create a Simple REST API

#### Description
Build a FastAPI application that manages a collection of books. The API should allow users to view, add, update, and delete books.

#### Requirements
Completed program should:

- Provide endpoints to list all books, add a new book, update an existing book, and delete a book
- Store books in an in-memory list (no database required)
- Each book should have an id, title, and author
- Validate input data (e.g., title and author must not be empty)
- Return appropriate HTTP status codes for each operation

### 🛠️ Add Extra Features

#### Description
Enhance your API to make it more robust and user-friendly.

#### Requirements
Completed program should:

- Add endpoint to get a single book by its id
- Handle errors gracefully (e.g., book not found)
- Add OpenAPI documentation (FastAPI provides this automatically)
- (Optional) Allow searching books by title or author

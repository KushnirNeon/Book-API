# Book API

A simple **Azure Functions** REST API to manage a collection of books in memory.

## Features

- Get all books
- Get a single book by ID
- Create a new book
- Update an existing book
- Delete a book

## API Endpoints

| Method | Route           | Description                |
|--------|----------------|----------------------------|
| GET    | `/get`          | Retrieve all books         |
| GET    | `/get/{id}`     | Retrieve a book by ID      |
| POST   | `/post`         | Create a new book          |
| PUT    | `/put/{id}`     | Update a book by ID        |
| DELETE | `/delete/{id}`  | Delete a book by ID        |

## Book Object

```json
{
  "Title": "Book Title",
  "Author": "Author Name",
  "PageCount": 123,
  "Id": "auto-generated GUID"
}

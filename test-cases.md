Test Cases for API Endpoints
1. GET /books/{id}
Test Case: Retrieve a book by ID.

Input: GET /books/1

Expected Output:

Status code: 200 OK

Response body with book details (title, author, etc.)

2. POST /books
Test Case: Add a new book.

Input:

json
Copy
Edit
{
  "title": "New Book",
  "author": "Author Name"
}
Expected Output:

Status code: 201 Created

Response body containing new book details.

3. PATCH /books/{id}
Test Case: Update book information.

Input:

json
Copy
Edit
{
  "title": "Updated Book Title"
}
Expected Output:

Status code: 200 OK

Response body showing updated book details.

4. DELETE /books/{id}
Test Case: Delete a book by ID.

Input: DELETE /books/1

Expected Output:

Status code: 204 No Content

Response body empty or success message.

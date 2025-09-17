![WhatsApp Image 2025-09-13 at 16 57 40_dc4ef4c6](https://github.com/user-attachments/assets/badbbba7-1138-4705-9dc7-b036cadb5157)

![WhatsApp Image 2025-09-17 at 19 37 02_08a4b615](https://github.com/user-attachments/assets/01ed7feb-a6c0-431f-a5b6-7e652707f2d2)


The following screenshots demonstrate how Mongoose schema validation works in our Express.js REST API:

Validation Error Example

When a request is sent with only the email field and missing required fields (name, age), the server responds with a 400 Bad Request.

The response clearly shows which fields are missing and returns custom validation error messages.

Successful Student Creation

When all required fields (name, email, age) are provided with valid values, the student document is successfully created in MongoDB.

The server responds with 201 Created along with the saved student object.

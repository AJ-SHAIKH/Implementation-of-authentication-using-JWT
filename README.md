✅ Summary: Student API with JWT Authentication This project is a secure RESTful API built using Node.js, Express, MongoDB, and JWT. It enables authenticated users to perform CRUD operations on student data.

🔐 Authentication Uses JWT tokens for user login and route protection.

Only logged-in users can access student-related endpoints.

🧱 Key Features Login with email & password

Add, View, Update, Delete student records

All operations require a valid JWT token

🗃️ Tech Stack Node.js & Express (server & routing)
![453564950-79dc37c7-b76f-4bd1-a790-81e021db9253](https://github.com/user-attachments/assets/9da369a6-f486-4ca8-bd35-e14d55ddeb2d)

MongoDB (database)

JWT (authentication)

bcryptjs (password hashing)

🔍 Testing Tested using Postman.

Endpoints:

POST /api/login

GET /api/students

POST /api/students

PUT /api/students/:id

DELETE /api/students/:id![453564863-81166fbc-bf84-49a3-b306-5f5e0d5a196e](https://github.com/user-attachments/assets/bfae1efa-3bea-4010-b930-5ab07a0ad92e)


🎓 Use Case Demonstrates secure API development with route protection, middleware, and token-based access control.

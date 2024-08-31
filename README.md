Course Acad - Backend
Course Acad is an online learning platform designed to offer a variety of courses to users. This repository contains the backend code, built using Node.js and MongoDB, and integrated with Razorpay for secure and efficient payment processing.

Features
User Management: Includes user registration, login, and profile management.
Course Management: Provides functionalities to create, update, delete, and manage courses.
Payment Integration: Seamlessly integrated with Razorpay to handle secure payments.
Authentication and Authorization: Secure authentication using JWT tokens and middleware for protected routes.
Error Handling: Centralized error handling for improved debugging and user experience.
File Uploads: Supports file uploads using Multer.

Folder Structure
config/: Contains configuration files like database connection.
controllers/: Includes all controllers for handling requests and responses.
courseController.js
otherController.js
paymentController.js
userController.js
middlewares/: Contains middleware functions such as authentication, error handling, etc.
models/: MongoDB models for different entities such as users, courses, payments, etc.
routes/: Defines all the routes for various endpoints.
courseRoutes.js
otherRoutes.js
paymentRoutes.js
userRoutes.js
utils/: Utility functions like error handlers, email sending, token generation, etc.
app.js: Entry point of the application.
server.js: Configures and starts the server.

Installation
Clone the repository:
git clone https://github.com/ershiva23/course-acad-backend.git

Install the dependencies:
npm install
Set up environment variables:
Create a .env file in the root directory.
Add the following variables:

PORT=5000
MONGO_URI=<Your MongoDB URI>
JWT_SECRET=<Your JWT Secret>

SMTP_HOST=<Your SMTP Host>
SMTP_PORT=<Your SMTP Port>
SMTP_USER=<Your SMTP User>
SMTP_PASS=<Your SMTP Password>

CLOUDINARY_CLIENT_NAME=<Your Cloudinary Client Name>
CLOUDINARY_CLIENT_API=<Your Cloudinary API Key>
CLOUDINARY_CLIENT_SECRET=<Your Cloudinary Secret Key>

RAZORPAY_API_KEY=<Your Razorpay API Key>
RAZORPAY_API_SECRET=<Your Razorpay Secret Key>
PLAN_ID=<Your Plan ID>

MY_MAIL=<Your Email Address>
REFUND_DAYS=7


Running the Application
Start the server:
npm start
The application will run on http://localhost:5000.
Contributions
Feel free to fork this repository and contribute by submitting a pull request.

License
This project is licensed under the MIT License.
